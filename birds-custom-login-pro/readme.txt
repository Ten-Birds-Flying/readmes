=== Birds Custom Login - Pro ===
Contributors: fredserva
Tags: admin, brand login, branded login, custom login, custom login color, custom login logo, french, log in, login, login page, logo, style log in, style login, themes
Requires at least: 4.9
Tested up to: 5.5
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html
Stable tag: 2.0.0
Requires PHP: 7.0.31

== Description ==

Birds Custom Login allows you to easily customize your admin login page according to your needs.

This plugin is compatible with all of WordPress' built-in functionalities and logout links will still function as they should.

If no logo is uploaded, the default WordPress logo is shown.

Live preview your Login Page in the plugin settings page. No need to Log Out!

This plugin is Localization/Internationalization ready and follows WordPress i18n standards.


== Installation ==

1. Unzip plugin files and upload them under your '/wp-content/plugins/' directory.
2. Resulted names will be: '/wp-content/plugins/birds-custom-login-pro/'
3. Activate plugin at "Plugins" administration page.


== Frequently Asked Questions ==

= Can I revert to original wordpress template? =

Yes, just click the 'Reset all settings' button.

= What is the recommened logo size? =

Less than or equal to 320px width and 200px height is the recommended logo size for your WordPress Login Page.

== Screenshots ==

1. Dashboard

== Changelog ==

= 2.0 =

* New feature: Fullwidth preview
* New feature: Google Fonts for labels
* New feature: Gradient background generator
* New feature: Background images slideshow
* New feature: YouTube video background
* New feature: New licensing method
* New feature: GDPR Privacy Policy Link customization
* New feature: Welcome Message Box
	* Title
	* Auto close
	* Auto close timer
	* Styles
	* Dimensions
* New feature: Login Form position
* New feature: Remember Me checkbox checked (or not)
* Changed: Position and icon in WP menu
* Changed: Options Framework
* Changed: Text domain according to WP standards
* Changed: All code reformatted according to WP coding standards
* Changed: Changelog Handling method
* Changed: Updates Handling methods
* Changed: Refactor Admin UI
* Changed: Some dependencies updates

= 1.3 =

* Changed: Text domain according to WP standards
* Changed: All code reformatted according to WP coding standards
* Changed: Some dependencies updates
* Changed: Changelog Handling method
* Changed: Updates Handling methods
* Changed: Better display for logo preview in admin settings (if png with transparency)
* Added: New licensing method
* Added: Google Fonts for labels

= 1.2.11 =

* Fixed: Bug with Color Picker. Updated to last version (2.1.3)
* Fixed: Bug on database reset

= 1.2.10 =

* Fixed for good: Get image size method
* Changed: Input Icons positions
* Changed: Some typos in french translation

= 1.2.9 =

* Fixed: Bug with new get image size method if allow_url_fopen = 1

= 1.2.8 =

* Changed: Method to get uploaded logos height and width
* Added: Condition for updating from free version
* Fixed: Redirection according to user role
* Some CSS Change for better WP 4.7+ compatibility

= 1.2.7 =

* Fixed: Vaultpress Generic Bad Pattern Warning
* Replaced http with https in Ten Birds Flying URLs for security reasons

= 1.2.6 =

* Added: Condition for Custom curl_get_contents
* Added: Condition for loading CSS only in settings page
* Some Admin CSS Change

= 1.2.5 =

* Some CSS Change for better WP 4.4+ compatibility
* Added: Link to external CSS file
* Added: New API for updates and license renewal
* Added: Russian translation

= 1.2.4 =

* Full WP 4.4 compatibility
* Added Custom Tooltip Text for logo
* Some code improvement

= 1.2.3 =

* Fixed: jQuery conflict

= 1.2.2 =

* Fixed: Settings not updating correctly.

= 1.2 =

* Added Choice between WordPress Default Message Boxes or Popups
* If Popups:
    - Welcome Message with Title, text, auto close timer (or not), auto close delay. This message is displayed on the login page only. Not on the logout one.
* Added Choice between Login Shake Effect or not when a login error is displayed
* Added Choice between WordPress Default Error messages or a Generic one (better security)
* Fixed Chrome auto-fills conflict with WordPress’s native code
* Fixed Chrome forced yellow input background (partially: works only if input background color opacity is equal to 1)
* Changed Media Uploader method
* Added Custom jQuery textarea
* Added Login Attempts Limitation (can be disabled)
* Added Retina logo support

= 1.1 =

* Code Cleaning
* More secure Custom CSS textarea sanitization
* Added Login with email or username
* Added Redirection according to user role (WordPress pre-defined roles & WooCommerce)
* Added Username & Password Input Icons
* Nicer notices

= 1.0 =

* Initial Release

== Upgrade Notice ==

### 2.0 ###
This is mainly a maintenance release which updates the readme and the plugin authors.
