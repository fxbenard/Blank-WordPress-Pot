# Blank WordPress Pot #

Author URI: http://fxbenard.com  
Contributors: Fx Bénard aka FxB   
Tags: i18n, translation, blank, pot  
Requires at least: WordPress  
Tested up to: 3.5 
Stable tag: 0.1.    
License: GPLv3 or Later.  

Blank WordPress Pot allows developpers to have a great starting point for their translations pot files and translators an explanation HowTo use the file.

## Description ##

Developpers and translators sometimes get a little confused when they want to start translating their WordPress files. Blank WordPress Pot provides the starting point to create the Ready to Translate .pot file.
In a few clicks your WordPress's plugin or extension will be ready to incorporate your translated strings. No more default.po or .pot without the right settings.


### Features of the files include ###

* Right propreties set (utf-8, plurals).
* Right path set.
* All keywords include.

* A How To file for translators to explain how to use the pot file


### How does it work? ###

1. Create the "languages" folder right at the base of your root folder.
2. Put Blank-WordPress.pot and the HowTo file inside.
3. Rename Blank-WordPress.pot with the slug of your plugin or extension.
4. In catalog -> preferences -> settings : change the properties to match your WordPress file name -> ok.
5. Push the update button in poedit main ui to fetch and update the translated strings.
6. Save (if a notice ask you to pick a language just pick "none of this"). Use your textdomain name if it's a plugin or only en_US for the name of your file.
7. Exit and that's it. 

Now the translators have a pot file ready to be used, and an HowTo to tell them what to do in case of need.  
No more hassle for you and for them...