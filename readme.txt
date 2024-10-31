=== RTL Tester Mirror by WebMan ===

Contributors:      webmandesign
Donate link:       https://www.webmandesign.eu/contact/#donation
Author URI:        https://www.webmandesign.eu/
Plugin URI:        https://www.webmandesign.eu/portfolio/rtl-tester-mirror-wordpress-plugin/
Requires at least: 6.0
Tested up to:      6.7
Requires PHP:      7.0
Stable tag:        1.0.5
License:           GPL-3.0-or-later
License URI:       http://www.gnu.org/licenses/gpl-3.0.html
Tags:              rtl, ltr, testing, mirror, transform

Makes it easy for LTR language speaker to test the RTL website layout by mirroring it so it looks like LTR.


== Description ==

This plugin simply mirrors the Right To Left (RTL) website layout using a CSS transform making it look like Left To Right (LTR) website.

This is a great tool for LTR language speakers for testing RTL layouts of WordPress themes and plugins, making the testing process much easier for you eyes and brain ;)

Works great with [RTL Tester](https://wordpress.org/plugins/rtl-tester/) plugin.

= Features =

* Mirrors RTL website layout to make it look like LTR layout
* Plugin adds a blue notification with "Mirrored RTL" text at the top when the RTL website is mirrored

= Plugin Localization =

Translate the plugin by clicking the **"Translate RTL Tester Mirror"** button under the "Translations" section in the sidebar.

= Additional Resources =

* [Write a review](https://wordpress.org/support/view/plugin-reviews/rtl-tester-mirror/#postform)
* [Have a question?](https://wordpress.org/support/plugin/rtl-tester-mirror/)
* [Grab a free theme](https://profiles.wordpress.org/webmandesign/#content-themes)
* [Follow @webmandesigneu](https://twitter.com/webmandesigneu/)
* [Visit WebMan Design](http://www.webmandesign.eu)


== Installation ==

1. Unzip the plugin download file and upload `rtl-tester-mirror` folder into the `/wp-content/plugins/` directory.
2. Activate the plugin through the *"Plugins"* menu in WordPress.
3. Switch your website into RTL layout (with [RTL Tester](https://wordpress.org/plugins/rtl-tester/) plugin, for example).


== Frequently Asked Questions ==

= The WordPress toolbar no longer sticks! How come? =

Well, this seems to be a bug with your browser. The plugin actually applies a CSS transform on a `html` tag and some browsers can't cope with fixed positioned elements than. Sorry for inconvenience, but there is no real fix for this as of now. But I believe this is a small issue in comparison of the value the plugin gives you ;)

= Fixed positioned elements are not working, help! =

Well, the same as above...


== Screenshots ==

1. Standard LTR website layout
2. Standard RTL website layout when testing using "RTL Tester" plugin
3. Mirrored RTL website using the "RTL Tester Mirror by WebMan" plugin


== Changelog ==

= 1.0.4 =
* **Fix**: Fixing texts

= 1.0.3 =
* **Update**: Removing border around the mirrored website in favor of simple notification at the top
* **Update**: Function name
* **Fix**: Fixing localization issue

= 1.0.2 =
* **Update**: Renaming plugin
* **Update**: Uploading screenshots

= 1.0.1 =
* **Fix**: Fixing typos

= 1.0 =
* Initial release.


== Upgrade Notice ==

= 1.0.4 =
Fixing texts.

= 1.0.3 =
Removing border around the mirrored website in favor of simple notification at the top, updating function name, fixing localization issue.

= 1.0.2 =
Changing plugin name, uploading screenshots.

= 1.0.1 =
Fixing typos.

= 1.0 =
This is initial plugin release.
