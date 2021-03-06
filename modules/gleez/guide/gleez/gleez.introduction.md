I. Introduction
---------------

Gleez is the fusion of many good concepts from the 3 most popular CMS: Joomla, Drupal and Wordpress and ruby rails. 
With years of experience using these, we've gathered great ideas and in some cases, improved on them.
But creating this CMS quickly would have been nearly impossible without its foundational framework - Kohana 3.

**Some terms used in Gleez:**

* **Modules** - code that extends the functionalities of Gleez. Kohana just calls them "Modules", others call it "Plugins"(Wordpress) or "Modules"(Drupal), but it's a more general term. Everything you can use for Gleez is an Extension.
* **Widgets** - the mini content boxes of a page. Others call it "Modules"(Joomla), "Blocks"(Drupal), and also "Widgets"(Wordpress)
* **Events** - functions or methods that execute on certain events during the runtime of Gleez. Others call it "Plugins"(Joomla), "Hooks"(Drupal)
* **Vendors** - 3rd party libraries that can be instantiated to aid in programming
* **Themes** - the look and layout of a Gleez site. Themes dictate the layout of contents in a Gleez page. It is very similar to Joomla's Template system.

**What is Kohana 3?**

Kohana 3 is an HMVC(Hierarchical Model View Controller) framework written on PHP that lets developers create web applications easier and faster. Perhaps you've heard of the MVC architectural pattern. 
Frameworks like Ruby on Rails, Django, CodeIgniter, CakePHP, and many others use MVC. Kohana 3 is a little different because it is using the HMVC pattern. 
HMVC is deemed as the "logical" evolution of MVC. HMVC can be quickly described as an MVC that can have children MVC's. For a detailed description of the advantages of HMVC,
check [this article](http://techportal.ibuildings.com/2010/02/22/scaling-web-applications-with-hmvc).

**There's nothing you can't extend**

Those already familiar with Kohana 3 will know that any CMS or web application built on top of it will be very easy to extend and customize. Kohana 3's major feature is not only its ***HMVC architectural pattern*** but also its ***Cascading File System***. 
This clever and unique filesystem allows developers to extend or override anything, any extension for Gleez is extendable and overridable, even Gleez's and Kohana 3's Core files. 
Websites built with Gleez can be fully customized without hacking any core file.

**What is Gleez then?**

Kohana 3 is a lean and mean framework, it does nothing else but to provide developers with libraries and simple, non-restrictive patterns that make building web applications faster and easier than many other frameworks.
Gleez is simply a module for Kohana 3. It mainly provides the user interfaces(GUI) and libraries, and some additional conventions to easily manage a website system. 

Gleez provides the user interface to manage many aspects of a website like the following:

* Website Navigation and Web Pages
* Users, User Groups, and Permissions
* Contents or Articles for News or Blogging
* Content Categories
* Content Comments
* Content Tagging
* Content Blocks or Widgets
* Extensions, Modules or Plugins
* Themes and Layouts
* Input formats like Markdown, HTML etc
* Shortcodes
* oAuth2 login via Google/Facebook/Windows
* Resize images on fly with caching
* Other Details like SEO, Media, etc.

**Frameworks & Libraries**

* Kohana    [(http://kohanaframework.org)](http://kohanaframework.org)
* Bootstrap Twitter [(http://twitter.github.com/bootstrap/)](http://twitter.github.com/bootstrap/)
* jQuery [(http://jquery.com/)](http://jquery.com/)
* Font Awesome [(http://fortawesome.github.com/Font-Awesome/)](http://fortawesome.github.com/Font-Awesome/)
* Select2 jQuery plugin [(http://ivaynberg.github.com/select2/)](http://ivaynberg.github.com/select2/)
* DataTables jQuery plugin [(http://datatables.net/)](http://datatables.net/)
* Redactor jQuery plugin [(https://github.com/dybskiy/redactor-js/)](https://github.com/dybskiy/redactor-js)
* PHP Markdown [(http://michelf.ca/projects/php-markdown/)](http://michelf.ca/projects/php-markdown/)
* PHPMailer [(https://github.com/Synchro/PHPMailer/)](https://github.com/Synchro/PHPMailer/)

**Credits**

* Drupal    [(http://www.drupal.org)](http://www.drupal.org)
* Gallery3  [(http://gallery.menalto.com)](http://gallery.menalto.com)
* Kerkness  [(http://kerkness.ca/wiki/doku.php)](http://kerkness.ca/wiki/doku.php)
* BoltCMS   [(http://github.com/boltcms/bolt)](http://github.com/boltcms/bolt)
* s7nCMS    [(http://code.google.com/p/s7ncms/)](http://code.google.com/p/s7ncms/)
* Kohanut   [(http://kohanut.com/)](http://kohanut.com/)
* Wordpress [(http://wordpress.org)](http://wordpress.org)

We've lifted some codes from these applications and felt this is palce for giving credit to them as demanded!
