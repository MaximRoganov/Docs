---
title: Время жизни
translation: caching/
---

Общей необходимостью является способность контролировать, как долго должен жить фрагмент данных - как долго, прежде чем срок его действия истекает и он больше не годится? Точно так же, как с бутылками молока, знание даты истечения срока действия может сказать нам, являются ли наши данные все еще хорошими или нам нужно пересчитать их.

## Создадим сниппет

В этом примере мы собираемся создать сниппет, который хранит немного данных в течение короткого периода времени. Вставьте следующий фрагмент кода в новый сниппет с именем «testCache», а затем сохраните его.

```php
<?php
$cacheManager = $modx->getCacheManager();

$lifetime = 10; // in seconds

if (!$payload = $cacheManager->get('my_cache_key')) {
    $payload = date('H:i:s');
    $cacheManager->set('my_cache_key',$payload, $lifetime);
}

return $payload;
```

Хитрость в том, что вывод из cacheManager будет нулевым, если данные либо не существуют, либо истек срок их действия.

## Вызовем сниппет

Когда вы вызываете сниппет, использующий пользовательское кэширование, как показано ниже, вы *должны* вызвать его некэшированным. Это обходит стандартные механизмы кэширования и позволяет вашему коду взять кэширование в свои руки.

```php
[[!testCache]]
```

## Посмотрим на результат

Обновляйте часто страницу, содержащую сниппет `testCache`, и смотрите на вывод информации. Вы должны заметить, что отметка даты обновляется только каждые 10 секунд!

Когда вы очищаете кэш сайта, ваши кэшированные данные будут также очищаться, поэтому вы можете запустить новую метку даты, очистив кэш вашего сайта (это будет немного проще заметить, если вы увеличите время жизни до 60 секунд или около того).

Если вы хотите, чтобы ваши данные оставались неизменными даже после того, как пользователь очистил кэш сайта, вам нужно настроить собственный раздел кэширования - читайте об этом в другом разделе. Приведенный здесь пример идеально подходит для кэширования данных, имеющих отношение к страницам, поскольку кэш будет очищен при обновлении страницы.

## Резюме

Установка пользовательских времен жизни для ваших кэшированных данных может быть отличным способом помочь вашему сайту снять нагрузку. Кэширование данных даже на одну или две минуты (или даже на несколько секунд) может иметь значение для нагрузки на сервер. В нашем примере мы рассчитываем текущую дату в демонстрационных целях, но подумайте о том, как этот метод может сэкономить циклы процессора, когда вычисляемые вами данные особенно тяжелы, например, интенсивный запрос к базе данных или медленный вызов API.
