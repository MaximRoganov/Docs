---
title: "Permissions - Administrator Policy"
_old_id: "218"
_old_uri: "2.x/administering-your-site/security/policies/permissions/permissions-administrator-policy"
---

The Administrator Policy
------------------------

This policy is packaged into MODx and is given to users on the 'mgr' context who want to have full access to managing MODx content.

Default Permissions
-------------------

<table><tbody><tr><th>Name</th><th>Description of Access</th></tr><tr><td>about</td><td>The About page.</td></tr><tr><td>access\_permissions</td><td>Any Access Permission-related pages and actions.</td></tr><tr><td>action\_ok</td></tr><tr><td>actions</td><td>The [Actions](developing-in-modx/advanced-development/custom-manager-pages/actions-and-menus "Actions and Menus") page.</td></tr><tr><td>change\_password</td><td>User can change their user password.</td></tr><tr><td>change\_profile</td><td>User can change their profile.</td></tr><tr><td>content\_types</td><td>The [Content Types](making-sites-with-modx/structuring-your-site/resources/content-types "Content Types") page.</td></tr><tr><td>create</td><td>Basic "create" access on objects.</td></tr><tr><td>credits</td><td>View the Credits page.</td></tr><tr><td>customize\_forms</td><td>View and manage the [Customizing the Manager](administering-your-site/customizing-the-manager "Customizing the Manager") page.</td></tr><tr><td>database</td><td>The System Info page</td></tr><tr><td>database\_truncate</td><td>The ability to truncate a database table.</td></tr><tr><td>delete\_category</td><td>To delete or remove any Categories.</td></tr><tr><td>delete\_chunk</td><td>To delete or remove any [Chunks](making-sites-with-modx/structuring-your-site/chunks "Chunks").</td></tr><tr><td>delete\_context</td><td>To delete or remove any [Contexts](administering-your-site/contexts "Contexts").</td></tr><tr><td>delete\_document</td><td>To delete or remove any [Resources](making-sites-with-modx/structuring-your-site/resources "Resources").</td></tr><tr><td>delete\_eventlog</td><td>To empty the Event Log.</td></tr><tr><td>delete\_plugin</td><td>To delete or remove any [Plugins](developing-in-modx/basic-development/plugins "Plugins").</td></tr><tr><td>delete\_snippet</td><td>To delete or remove any [Snippets](developing-in-modx/basic-development/snippets "Snippets").</td></tr><tr><td>delete\_template</td><td>To delete or remove any [Templates](making-sites-with-modx/structuring-your-site/templates "Templates").</td></tr><tr><td>delete\_tv</td><td>To delete or remove any [Template Variables](making-sites-with-modx/customizing-content/template-variables "Template Variables").</td></tr><tr><td>delete\_role</td><td>To delete or remove any [Roles](administering-your-site/security/roles "Roles").</td></tr><tr><td>delete\_user</td><td>To delete or remove any [Users](administering-your-site/security/users "Users").</td></tr><tr><td>edit\_category</td><td>To edit any Categories.</td></tr><tr><td>edit\_chunk</td><td>To edit any [Chunks](making-sites-with-modx/structuring-your-site/chunks "Chunks").</td></tr><tr><td>edit\_context</td><td>To edit any [Contexts](administering-your-site/contexts "Contexts").</td></tr><tr><td>edit\_document</td><td>To edit any [Resources](making-sites-with-modx/structuring-your-site/resources "Resources").</td></tr><tr><td>edit\_locked</td><td>Allows a user to override a lock and edit a locked Resource.</td></tr><tr><td>edit\_parser</td></tr><tr><td>edit\_plugin</td><td>To edit any [Plugins](developing-in-modx/basic-development/plugins "Plugins").</td></tr><tr><td>edit\_role</td><td>To edit any [Roles](administering-your-site/security/roles "Roles").</td></tr><tr><td>edit\_snippet</td><td>To edit any [Snippets](developing-in-modx/basic-development/snippets "Snippets").</td></tr><tr><td>edit\_template</td><td>To edit any [Templates](making-sites-with-modx/structuring-your-site/templates "Templates").</td></tr><tr><td>edit\_tv</td><td>To edit any [Template Variables](making-sites-with-modx/customizing-content/template-variables "Template Variables").</td></tr><tr><td>edit\_user</td><td>To edit any [User](administering-your-site/security/users "Users").</td></tr><tr><td>element\_tree</td><td>The ability to view the Elements Tree on the left nav.</td></tr><tr><td>empty\_cache</td><td>To empty the site cache.</td></tr><tr><td>export\_static</td><td>To export the site to static HTML.</td></tr><tr><td>file\_manager</td><td>To use the file manager, including creating/deleting files.</td></tr><tr><td>file\_tree</td><td>To view the Files Tree on the left nav.</td></tr><tr><td>flush\_sessions</td><td>Can flush Sessions across the site.</td></tr><tr><td>frames</td><td>To use the MODx Manager UI at all.</td></tr><tr><td>help</td><td>To view the Help page.</td></tr><tr><td>home</td><td>To view the Welcome page.</td></tr><tr><td>import\_static</td><td>To view or use the Import pages.</td></tr><tr><td>languages</td><td>To edit or view Lexicon Languages.</td></tr><tr><td>lexicons</td><td>To edit or view Lexicons and [Internationalization](developing-in-modx/advanced-development/internationalization "Internationalization").</td></tr><tr><td>list</td><td>Basic permission to "list" any object. List means to get a collection of objects.</td></tr><tr><td>load</td><td>Basic permission to "load" any object, or be able to return it as an instance at all.</td></tr><tr><td>logout</td><td>To be able to logout as a user.</td></tr><tr><td>logs</td><td>To view the logs, such as error and manager logs.</td></tr><tr><td>menus</td><td>To edit or save any top Menu items.</td></tr><tr><td>messages</td><td>To send or view any personal Messages.</td></tr><tr><td>namespaces</td><td>To edit or view [Namespaces](developing-in-modx/advanced-development/namespaces "Namespaces").</td></tr><tr><td>new\_category</td><td>To create a new Category.</td></tr><tr><td>new\_chunk</td><td>To create a new [Chunk](making-sites-with-modx/structuring-your-site/chunks "Chunks").</td></tr><tr><td>new\_context</td><td>To create a new [Context](administering-your-site/contexts "Contexts").</td></tr><tr><td>new\_document</td><td>To create a new [Resources](making-sites-with-modx/structuring-your-site/resources "Resources").</td></tr><tr><td>new\_plugin</td><td>To create a new [Plugin](developing-in-modx/basic-development/plugins "Plugins").</td></tr><tr><td>new\_role</td><td>To create a new [Role](administering-your-site/security/roles "Roles").</td></tr><tr><td>new\_snippet</td><td>To create a new [Snippet](developing-in-modx/basic-development/snippets "Snippets").</td></tr><tr><td>new\_template</td><td>To create a new [Template](making-sites-with-modx/structuring-your-site/templates "Templates").</td></tr><tr><td>new\_tv</td><td>To create a new [Template Variable](making-sites-with-modx/customizing-content/template-variables "Template Variables").</td></tr><tr><td>new\_user</td><td>To create a new [User](administering-your-site/security/users "Users").</td></tr><tr><td>packages</td><td>To use any Transport Packages in the [Package Management](developing-in-modx/advanced-development/package-management "Package Management") system.</td></tr><tr><td>property\_sets</td><td>To view and edit [Properties and Property Sets](making-sites-with-modx/customizing-content/properties-and-property-sets "Properties and Property Sets").</td></tr><tr><td>providers</td><td>To view and edit [Providers](developing-in-modx/advanced-development/package-management/providers "Providers") across the site.</td></tr><tr><td>publish\_document</td><td>To publish or unpublish any Resource.</td></tr><tr><td>purge\_deleted</td><td>To empty the Recycle Bin.</td></tr><tr><td>remove</td><td>Basic permission to remove any object.</td></tr><tr><td>remove\_locks</td><td>To remove all existing Locks throughout the site.</td></tr><tr><td>resource\_tree</td><td>To view the Resource Tree in the left nav.</td></tr><tr><td>save</td><td>Basic save permission for any object.</td></tr><tr><td>save\_category</td><td>To save any Categories.</td></tr><tr><td>save\_chunk</td><td>To save any [Chunks](making-sites-with-modx/structuring-your-site/chunks "Chunks").</td></tr><tr><td>save\_context</td><td>To save any [Contexts](administering-your-site/contexts "Contexts").</td></tr><tr><td>save\_document</td><td>To save any [Resources](making-sites-with-modx/structuring-your-site/resources "Resources").</td></tr><tr><td>save\_plugin</td><td>To save any [Plugins](developing-in-modx/basic-development/plugins "Plugins").</td></tr><tr><td>save\_role</td><td>To save any [Roles](administering-your-site/security/roles "Roles").</td></tr><tr><td>save\_snippet</td><td>To save any [Snippets](developing-in-modx/basic-development/snippets "Snippets").</td></tr><tr><td>save\_template</td><td>To save any [Templates](making-sites-with-modx/structuring-your-site/templates "Templates").</td></tr><tr><td>save\_tv</td><td>To save any [Template Variables](making-sites-with-modx/customizing-content/template-variables "Template Variables").</td></tr><tr><td>save\_user</td><td>To save any [User](administering-your-site/security/users "Users").</td></tr><tr><td>search</td><td>To use the Search page.</td></tr><tr><td>settings</td><td>To view and edit any System Settings.</td></tr><tr><td>steal\_locks</td><td>To "steal" locks, overriding a current lock on a document.</td></tr><tr><td>unlock\_element\_properties</td><td>To be able to edit the default properties for any Element.</td></tr><tr><td>view</td><td>Basic permission to "view" any object.</td></tr><tr><td>view\_category</td><td>To view any Categories.</td></tr><tr><td>view\_chunk</td><td>To view any [Chunks](making-sites-with-modx/structuring-your-site/chunks "Chunks").</td></tr><tr><td>view\_context</td><td>To view any [Contexts](administering-your-site/contexts "Contexts").</td></tr><tr><td>view\_document</td><td>To view any [Resources](making-sites-with-modx/structuring-your-site/resources "Resources").</td></tr><tr><td>view\_eventlog</td><td>To view the Event Log.</td></tr><tr><td>view\_offline</td></tr><tr><td>view\_plugin</td><td>To view any [Plugins](developing-in-modx/basic-development/plugins "Plugins").</td></tr><tr><td>view\_role</td><td>To view any [Roles](administering-your-site/security/roles "Roles").</td></tr><tr><td>view\_snippet</td><td>To view any [Snippets](developing-in-modx/basic-development/snippets "Snippets").</td></tr><tr><td>view\_template</td><td>To view any [Templates](making-sites-with-modx/structuring-your-site/templates "Templates").</td></tr><tr><td>view\_tv</td><td>To view any [Template Variables](making-sites-with-modx/customizing-content/template-variables "Template Variables").</td></tr><tr><td>view\_unpublished</td><td>To view any unpublished [Resources](making-sites-with-modx/structuring-your-site/resources "Resources").</td></tr><tr><td>view\_user</td><td>To view any [User](administering-your-site/security/users "Users").</td></tr><tr><td>workspaces</td><td>To utilize [Package Management](developing-in-modx/advanced-development/package-management "Package Management").</td></tr></tbody></table>Custom Permissions
------------------

If you have created your own actions and menu items (e.g. if you have created a [Custom Manager Page](developing-in-modx/advanced-development/custom-manager-pages/custom-manager-pages-tutorial "Custom Manager Pages Tutorial")), then you can define custom permission items when you create the menu item (System --> Actions --> Create Menu) that correspond to permissions listed here.

![](/download/attachments/18678342/MODX+Custom+Permission.jpg?version=1&modificationDate=1331314961000)

See Also
--------

1. [Permissions - Administrator Policy](administering-your-site/security/policies/permissions/permissions-administrator-policy)
2. [Permissions - Resource Policy](administering-your-site/security/policies/permissions/permissions-resource-policy)