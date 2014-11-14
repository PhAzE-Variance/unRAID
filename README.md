unRAID Universal Plugins (32 & 64 Bit)
======

This repo hosts the unRAID universal plugins I've created.  These are re-writen from the original ones I made to be comaptible with both unRAID 5 and 6.

You will find the plugin files under the Plugins directory, and all the control and dependency files for each app are under the AppSupport folder.

You only require the plugin file to install these on your unRAID server, and the control and dependency files will be automatically downloaded.

Changes from V1 files:
- Stores a copy of the install files on USB
- Can install the plugin and app if there is no internet connection (and it has been installed at least once before with internet)
- MD5 or equivelent checking on all install and dependency files
- Shows dependency status on plugin GUI pages
- Can now turn off automatic update checks on plugin GUI when the page loads up
- Dependencies are all 'sandboxed' into a PhAzE-Common folder so unRAID core files are not modified
- Uninstall button has been added to remove the plugin and all install files
- Uninstall also removes dependencies but leave install and config directories intact
- Compatible with Plugin Manager in unRAID v6 beta 4 or higher

-=PhAzE=-