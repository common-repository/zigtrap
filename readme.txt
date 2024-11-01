=== ZigTrap ===
Contributors: ZigPress
Donate link: https://www.zigpress.com/donations/
Tags: honey trap, honey pot, comments, comment form, hidden field, spam trap, anti-spam, zig, zigpress, classicpress
Requires at least: 4.0
Tested up to: 5.4
Requires PHP: 5.3
Stable tag: 1.0

ZigTrap adds a honey trap to your comments form.

== Description ==

**Due to abuse received from plugin repository users we are ceasing development of free WordPress plugins and this is the last release of this plugin. It will be removed from the repository in due course. Our pro-bono plugin development will now be exclusively for the ClassicPress platform.**

ZigTrap adds a hidden field to your comments form, which humans will leave empty because they don't know it's there. Spam bots, however, will normally enter some content in it, and this springs the trap, causing WordPress to show a message and not save the comment at all.

Use this in conjunction with Akismet for a pretty solid spam prevention package.

Please ensure that the comments form in your theme calls the 'comment_form' action.

Compatible with ClassicPress.

For further information and support, please visit [the ZigTrap home page](https://www.zigpress.com/plugins/zigtrap/).

== Installation ==

1. Check that you are using WordPress 4.0 or greater, and PHP 5.3 or greater.
2. Unzip the installer and upload the resulting 'zigtrap' folder to the `/wp-content/plugins/` directory.  Alternatively, go to Admin > Plugins > Add New and enter ZigTrap in the search box.
3. Activate the plugin through the 'Plugins' menu in WordPress.

== Frequently Asked Questions ==

= Why isn't the counter working? =

* Please deactivate and reactivate the plugin, and check that you have the latest version.

= Where is the counter shown? =

* On the Admin Dashboard page, at the bottom of the "Right Now" panel.

= Why do I get this error when activating? "Parse error: syntax error, unexpected T_STRING, expecting T_OLD_FUNCTION or T_FUNCTION or T_VAR or '}' in ..." =

* Your server is running PHP4.  ZigTrap requires PHP5, as do all ZigPress plugins. PHP4 is dead.

For further information and support, please visit [the ZigTrap home page](https://www.zigpress.com/plugins/zigtrap/).

== Changelog ==

= 1.0 =
* Notice of cessation of free WordPress plugin development
= 0.4.2 =
* Verified compatibility with WordPress 5.3.x
* Verified compatibility with ClassicPress 1.1.x
* Changed name of trap field to keep foiling those spambots
= 0.4.1 =
* Verified compatibility with WordPress 5.2.x
* Verified compatibility with ClassicPress 1.0.x
= 0.4 =
* Verified compatibility with WordPress 4.9.8
* Verified compatibility with ClassicPress 1.0.0-beta1
* Changed name of trap field to keep foiling those spambots
= 0.3.14 =
* Confirmed compatibility with WordPress 4.9.7
* Changed name of trap field to keep foiling those spambots
= 0.3.13 =
* Confirmed compatibility with WordPress 4.9
* Changed name of trap field to keep foiling those spambots
= 0.3.12 =
* Confirmed compatibility with WordPress 4.8.x
= 0.3.11 =
* Confirmed compatibility with WordPress 4.7
* Changed name of trap field to keep foiling those spambots
= 0.3.10 =
* Confirmed compatibility with WordPress 4.6.1
= 0.3.9 =
* Confirmed compatibility with WordPress 4.5.3
= 0.3.8 =
* Confirmed compatibility with WordPress 4.4
* Increased minimum WordPress version to 4.0 in accordance with ZigPress policy of gradually dropping support for deprecated platforms
= 0.3.7 =
* Confirmed compatibility with WordPress 4.3
= 0.3.6 =
* Confirmed compatibility with WordPress 4.2
* Increased minimum PHP version to 5.3 in accordance with ZigPress policy of gradually dropping support for deprecated platforms
= 0.3.5 =
* Confirmed compatibility with WordPress 4.1
* Minimum compatible version raised to 3.6
= 0.3.4 =
* Confirmed compatibility with WordPress 3.9
* Changed name of trap field to keep foiling those spambots
= 0.3.3 =
* Changed name of trap field to keep foiling those spambots
* Updated donation link in readme
* Confirmed compatibility with WordPress 3.5.2
= 0.3.2 =
* Confirmed compatibility with WordPress 3.5
= 0.3.1 =
* Correction to plugin URL
= 0.3 =
* Confirmed compatibility with WordPress 3.4.2
* Changed code indentation and added some small code style improvements
* Changed name of trap field to keep foiling those spambots
* Updated plugin URL in header block to reflect new plugin homepage location
= 0.2.4 =
* Confirmed compatibility with WordPress 3.3.1
= 0.2.3 =
* Confirmed compatibility with WordPress 3.1.1
= 0.2.2 =
* Updated readme.txt to clarify PHP5 requirement
= 0.2.1 =
* Fix for the problem that meant manual deactivation and reactivation was sometimes necessary to start the counter going
= 0.2 =
* Added simple counter on dashboard
= 0.1 =
* First public release
