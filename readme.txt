=== UserAgent Content Switcher ===
Contributors: Katsushi Kawamori
Donate link: https://shop.riverforest-wp.info/donate/
Tags: Browser, phone, platform, useragent, web browser
Requires at least: 4.7
Requires PHP: 8.0
Tested up to: 6.6
Stable tag: 3.05
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Display the html written between the shortcode of each user agent.

== Description ==

Display the html written between the shortcode of each user agent.

* Can add a shortcode attribute value and set the corresponding user agent.
* Sibling plugin -> [UserAgent Themes Switcher](https://wordpress.org/plugins/useragent-themes-switcher/).

== Installation ==

1. Upload `useragent-content-switcher` directory to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Add a new Page
4. Write a short code. The following text field. `[agentsw]`

= How to use =

Please add new Page. Please write a short code in the text field of the Page. Please go in Text mode this task.

"UserAgent Content Switcher" activation, you to include additional buttons for Shortcode in the Text (HTML) mode of the WordPress editor.

Examples

[agentsw]
Please code the HTML for the PC here.
[/agentsw]

[agentsw ua='pc']
Please code the HTML for the PC here.
[/agentsw]

[agentsw ua='tb']
Please code the HTML for the Tablet here.
[/agentsw]

[agentsw ua='sp']
Please code the HTML for the Smartphone here.
[/agentsw]

[agentsw ua='mb']
Please code the HTML for the Featurephone here.
[/agentsw]

== Frequently Asked Questions ==

none

== Screenshots ==

1. Settings
2. Edit & Quick Tag

== Changelog ==

= 3.05 =
Supported WordPress 6.4.
PHP 8.0 is now required.

= 3.04 =
Supported WordPress 5.6.

= 3.03 =
Fixed admin screen.

= 3.02 =
The admin screen has been changed.

= 3.01 =
Fixed a problem with the form validation process when adding "Type".

= 3.00 =
Can add a shortcode attribute value and set the corresponding user agent.

= 2.39 =
Conformed to the WordPress coding standard.

= 2.38 =
Removed unnecessary code.

= 2.37 =
Fixed fine problem.

= 2.36 =
Changed donate link.

= 2.35 =
Add Quick Tag.
Fixed problem of management screen.

= 2.34 =
Fixed problem of Javascript.

= 2.33 =
Supported GlotPress.

= 2.32 =
/languages delete the directory.

= 2.31 =
Supported GlotPress.

= 2.3 =
Javascript and CSS will be loaded only to the required page.

= 2.2 =
Add screen of donate.
Change readme.txt.
Change /languages.

= 2.1 =
Fixed a problem of Java Script for admin screen.

= 2.0 =
Change management screen to responsive tab menu design.

= 1.1 =
Fixed of problem of error in debug mode.

= 1.0 =

== Upgrade Notice ==

= 1.0 =
