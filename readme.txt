=== CLUEVO LMS, E-Learning Platform ===
Contributors: cluevo
Donate link: https://cluevo.at/donate/
Tags: e-learning, lms, scorm, quiz, pdf, embed, learning, ai, membership, teaching, trainer, education
Stable tag: 1.13.2
Requires at least: 4.6
Tested up to: 6.4
Requires PHP: 5.6
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Transforms your WordPress into a powerful Learning Management System. Organize video tutorials, podcasts and interactive SCORM courses with quizzes and more.

== Description ==

= Introduction =
Welcome to the CLUEVO Learning Management System for WordPress. Our LMS allows you to add SCORM e-learning modules, video tutorials, podcasts and other media to your WordPress site. That Content can be organized into courses, chapters and modules and you can easily manage the permissions for different users and groups.

⭐ [Video Tutorials](https://tutorial.cluevo.at/)
⭐ [CLUEVO LMS Bundles](https://wp-lms.cluevo.at/pricing/)
⭐ [Create interactive E-learning Scorm Courses](https://wp-lms.cluevo.at/content-design/)

**Setup the CLUEVO Learning Tree Structure**
[youtube https://youtu.be/8C2DIuMAwQY]

= SCORM =
We currently support SCORM 2004 4th edition and SCORM 1.2. Other 2004 editions may work but are not officially supported. We are hard at work to provide better support for more versions of the standard. If you have any suggestions on what standards to support please don't hesitate to get in touch with us via the support Forum.

= Video/Audio =
Currently many File Formats like mp3, wav, mp4 and webm are supported. With our free oEmbed extension you can also add and organize videos from Youtube, twitch and other Streaming services.

= PDF =
CLUEVO LMS allows you to use your PDF files as learning modules. Upload a PDF file and use it as a module in your learning tree. Your users place in the document is stored and you can see each student's location in the document.

= Learning Structure =
The LMS consists of different courses that in turn contain chapters that contain modules. The first thing you'll want to do is upload a SCORM module. To do this use the uploader on the Learning Management page in the modules tab. Once you have uploaded one (or more!) modules you can start creating your learning structure. Create some courses and add chapters and modules. 

= User Management =
CLUEVO LMS gives you the ability to set permissions for each level of the learning tree. You can assign users to groups and set permissions for groups or just individual users. Each element of the learning tree can have one of three access levels:

0: No access. Items won't show up anyware for this user/group
1: Visible. Items will be visible for a user/group but cannot otherwise be accessed
2: Open. The user/group has full access to this element.

It is also possible to have permissions expire at a certain date/time.

Hint: As a user with administrative capabilities you have full access to all elements by default.

= Reports =
The reports page gives you an overview on the progress your users have made. You can also view the different SCORM parameters.
Progress records and SCORM parameters can also be exported to csv files.

= Competence =
The competence system allows you to define competence areas that consist of different competences. You can then set which modules teach which competences and how much of a competence a module covers.

An example could be that you have a competence area named Backoffice that consists of the following competences:
  
* Excel
* Word
* Outlook

Competences are a great alternative way to organize your courses. They enable your users to directly browse modules that teach certain competences.

= Settings =
CLUEVO LMS provides an in-depth settings page to customize the LMS to your liking. You can customize the way your modules are displayed, protect your modules from external access, allow your students to rate your content and much more.

= Extensions =
We offer a suite of extension to add functionality to your LMS. Whether it's support for more types of modules, certificates or reporting, we have it all.
Our Extension include:

== Free Extensions ==
* oEmbed Modules: Allows you to use content like YouTube videos as modules
* Google Documents: Let's you use your Google Docs as modules. With this you can just whip up a quick presentation and use it as a module

== Premium Extensions ==
* AI Quiz Maker: Transform your Posts into multiple choice quizzes with the push of a button
* Certificates: Design and issue certificates for when your users complete courses
* Multiple Trees: Create and manage more than one learning tree
* User Learning Progress: Adds new user focused reporting for trainers
* User Import: Import users with group memberships
* wooCommerce Integration: Let's you sell course access via wooCommerce products

== Your very own extension ==
We are always looking to improve on our LMS and also offer our services to implement extensions to your specifications. Feel free to inquire at info@cluevo.at for details.

== Now Available: AI Quiz Maker ==
We've recently released our AI Quiz Maker as a premium extension. This extensions allows you to create multiple-choice quizzes from your existint posts and pages or from copy and pasted text. We analyze your content generate quiz questions for you. You can then use these questions to compose your very own quiz modules.

= Support =
If you encounter any issues we recommend to submit a ticket via our support system found at cluevo.at -> produkte und dienstleistungen -> support. You can also use the WordPress support forums but response times via tickets are generally faster and we can offer more in depth help via ticket.

= Feedback =
If you have any feedback or feature requests please do not hesitate to contact us via the support Forum (https://wordpress.org/support/plugin/cluevo-lms/).

== Installation ==

1. Upload the plugin files to the `/wp-content/plugins/cluevo-lms` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress
3. Upload your SCORM modules and create a learning structure through the CLUEVO settings pages
4. Optionally set some permissions
5. Start learning (or teaching ;) )!

== Changelog ==
= 1.13.2 =
* Fixed tree element sort order
* Fixed an issue with saving modules display modes
* Added check for FileInfo functions

= 1.13.1 =
* Fixed limited attempts

= 1.13.0 =
* Reworked and optimized the reporting system
* Reworked and optimized tree system
* Settings page now uses vertical tabs
* Optimized loading of tree pages
* Added a database upgrade tool
* Optimized database by adding indexes where necessary
* Updated styling of admin pages to be more in line with the WordPress default styling

= 1.12.4 =
* Added a setting to automatically commit scorm parameters / progress when a module is completed
* Clear orphan permissions when deleting tree items
* Added missing translations

= 1.12.3 =
* Added options to select how to handle exising page content on CLUEVO assigned pages

= 1.12.2 =
* Use index page from settings for breadcrumbs index
* Respect permissions when displaying toc items

= 1.12.1 =
* Fixed iframe display mode if not configured for module
* Removed scroll offset when scrolling to iframe
* Changed iframe min-height to 100vhmin for better mobile experience

= 1.12.0 =
* Added a setting to set the default item list style for learning elements
* Added a setting to hide the list style switcher
* Added an argument to the cluevo shortcode to display a single item directly
* Added a setting to select a page to display the learning tree index
* Added a setting to select where to display the user profile page
* Added a setting to select where the login page is displayed
* Added a setting to enable the empty item message for elements without children or accessible children
* Fixed errors when guests attempt to view competence/area pages
* Fixed a bug that displayed an inaccurate message about attempts to guests (guests always have zero attempts, so they can't reach the limit)
* Fixed a bug that displayed a blank page when clicking the save button on the settings page without changing any settings
* Fixed some notices for guests
* Added proper support for exp points for media modules
* Fixed access resolution for points/level requirements
* Media modules (audio/video/pdf) now always update the existing progress record until it is completed
* Media modules count as success unknown until completed
* Ported frontend vue components to vue 3
* Fixed on page iframe module display

= 1.11.0 =
* Reworked the cluevo user page
* Updated the user page to display competences and competence areas
* Added pages to browse competences and areas
* Fixed pdf scaling on high dpi devices
* Allow redirecting the lms index page the first learning tree if only one tree is available
* Fixed some styling issues
* Added a shortcode for the user widget
* Module tree items now display the content page if the page's content is not empty
* Modules can now be started directly from the competence page
* Fixed a bug that reset existing attempts when using the iframe display mode
* Use 100svh for on page iframe modules
* Fixed format of cmi.core.student_name to conform to standards
* Fixed a security issue with saving the tree

= 1.10.0 =
* Added a setting to toggle display of item types on tiles
* Fixed an issue with loading pdf modules as guest users
* Fixed an issue where the lightbox would close even if module rating was triggered
* Fixed limited number of attempts for pdf modules

== Frequently Asked Questions ==

= My module fails to upload =
Please check your PHP max. script execution time and increase it if necessary. Your hosting provider can adjust this value for you.

= I can't see my content =

Make sure you are logged in or that you have set the permissions for the guest group accordingly.

= How do I access my learning content? =

You can add a link to the course index page through the menu editor or add a shortcode to any page where you want to display cluevo content

= How to I get a shortcode? =

You can copy the shortcode by using the [s] buttons for each element on the learning management page or by clicking on the item id that appears when you move your mouse over an item.
The shortcode supports two parameters: row and tile. By using these parameters you can set how the item is displayed on the page. You can also display elements as links by using the shortcode style [cluevo item="x"]This is a link[/cluevo]

= Can i display my modules on arbitrary pages? =

Absolutely! Just an items shortcode with the [s] button on the tree page and insert the shortcode where you want to display your module

= Do you take feature requests? = 

Absolutely! Do not hesitate to contact us via the support Forum (https://wordpress.org/support/plugin/cluevo-lms/) or send your requests to wp@cluevo.at! For more expansive features we're happy to get back to you with a quote.

== Upgrade Notice ==
= 1.13.0 =
Reworked reporting system, optimizations

= 1.12.4 =
Added auto commit on completion setting

= 1.12.3 =
Added cluevo page content settings

= 1.12.2 =
Bugfixes

= 1.12.1 =
Bugfixes

= 1.12.0 =
Added custom page settings

= 1.11.0 =
User page rework + security fixes

== Screenshots ==
1. Creating a course structure
2. Handling permissions
3. User page
