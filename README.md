# Blank WordPress Pot #

Author URI: http://fxbenard.com
Contributors: Fx Bénard aka FxB
Tags: i18n, translation, blank, pot
Requires at least: WordPress
Tested up to: 4.1
Stable tag: 0.1.
License: GPLv3 or Later.

Blank WordPress Pot allows developers to have a great starting point for their translations' pot files and translators an explanation how to use the file.

## Description ##

Developers and translators sometimes get a little confused when they want to start translating their WordPress files. Blank WordPress Pot provides the starting point to create the ready to translate pot file.
In a few clicks your WordPress plugin or extension will be ready to incorporate your translated strings. No more default.po or .pot without the right settings.


### Features of the files include ###

* Right properties set (utf-8, plurals).
* Right path set.
* All keywords included.
* A how-to file for translators to explain how to use the pot file.


### How does it work? ###

1. Create the "languages" folder right at the base of your root folder.
2. Put Blank-WordPress.pot and the how-to file inside.
3. Rename Blank-WordPress.pot with the slug of your plugin or extension.
4. Open the file with Poedit.
5. In Catalog -> Properties -> Translation properties: change the properties to match your WordPress file name -> ok.
6. Push the update button in poedit main ui to fetch and update the translated strings.
7. Save (if a notice ask you to pick a language just pick "none of this"). Use your textdomain name if it's a plugin or only en_US for the name of your file.
8. Exit and that's it.

Now the translators have a pot file ready to be used, and an HowTo to tell them what to do in case of need.
No more hassle for you and for them...
