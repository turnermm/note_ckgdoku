# note_ckgdoku
Plugin to insert the note plugin source code in dokuwiki using the ckgdoku editor (https://github.com/turnermm/ckgdoku).

## Installation
Unzip the files to your `dokuwiki/lib/plugins/ckgedit/ckeditor/plugins/` folder and rename the folder to **note**.

## Dokuwiki configuration

Add the text **Note** to the dokuwiki **plugin»ckgedit»extra_plugins** configuration.

Edit the `dokuwiki/lib/plugins/ckgedit/ckeditor/config.js` file and add **note**.

###Example:
b.extraPlugins="signature,footnote,shortcuts,fontAssist,tags,timestamp,headerbuttons,**note**";

## Note: This plugin will work in either ckgdoku or ckgedit. 

It is no longer necessary to manually add this plugin to the `extra_plugins` list.  Instead, as above, unzip the plugin into the ckeditor plugins folder, and then add the plugin's toolbar button Name to the `extra_plugins` configuration option in the ckgdoku or ckgedit section of the Configuration Manager.  See the instructions in the ckgedit's documentation at dokuwiki.org: https://www.dokuwiki.org/plugin:ckgedit:configuration#extra_plugins. 
