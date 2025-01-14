=== Mimetic Books ===
Contributors: mimetic
Tags: Mimetic Books, Mimetic, iPad
Requires at least: 4.0
Tested up to: 4.5.3
Stable tag: 0.2.12
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

This plugin allows WordPress bloggers to publish books using the Mimetic Books publishing system.

== Description ==
This plugin allows WordPress bloggers to publish books using the Mimetic Books publishing system. The plugin handles both the creation of book packages from blog posts and the distribution of book packages to Mimetic Books-based apps.

For more information, see [Mimetic](http://mimetic.com/ "Mimetic").

== Installation ==
Install as usual.

Choose "Settings:Mimetic Books". 

Activate all the controllers.


== Frequently Asked Questions ==
Nothing yet.


== Changelog ==

= 0.2.12 =
* Tweak template for Ecosystem B

= 0.2.11 =
* Automatic uploads book packages to Amazon S3 storage so you don't have to serve them from your WordPress server, and you don't have to upload packages to S3 yourself.
* Automatically creates the presigned URL to get the Amazon S3 files for download.

= 0.2.10 =
* Updated the Ecosystem B theme

= 0.2.9 =
* Argh! Git issues! Fixed.

= 0.2.8 =
* The 'option' for a field in a template can now be a code instead of a pop-up menu option list. The only code right now is "!textarea". This code makes the field a textarea instead of a text field.

= 0.2.7 =
* Fixed resizing of images to fit templates.
* Fixed creation of extra -card files.

= 0.2.6 =
* Updated ecosystem-b theme, added cover template and updated overlays

= 0.2.5 =
* Retina backgrounds for ecosystem-b theme
* Fixed 'longevity' custom field values for ecosystem-b theme


= 0.2.4 =
* Added help text and pop-up menus for Mimetic Books Custom Fields, if defined in the templates file of a theme.
* Now the WordPress tags are captured and included in the book XML file, for use by page conditionals and plugins.
* Remove book publishing from the settings page


= 0.2.2 =
* Fixed the problem with jQuery popup dialogs not working since the WordPress update changed how jQuery worked.
* When the user choose a different book in "Mimetic Book Setings", the style chooser shows "Loading" while a new book template loads.
* Renamed the custom post type in the admin menus form "Book" to "Mimetic Books". Fixed the icon. Note that the post type is still "book", which certain can conflict with other plugins!

= 0.2.3 =
* Add an ecosystems cards theme.