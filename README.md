# Eole Foobar theme

This is a skin for the [foobar2000](https://www.foobar2000.org) audio player.
This theme require Foobar2000 1.4 (or superior).
Follow the [instructions below](README.md#installation) to install it properly

## Changes in this fork

I removed all network-related stuff (lyrics/biography downloads) and visualization for a less bloated and more privacy-preserving experience with the otherwise very nice Eole skin. I also changed the .fcl file so it defaults to dark mode and some minor tweaks.

## Preview

![preview image](preview.png)

## Installation

0. Close foobar.

1. Download this github repository and copy everything into your foobar profile directory (so the 2 folders: user-components and themes).
   - STANDARD foobar2000 installation: your foobar profile directory is in here: %AppData%/foobar2000
   - PORTABLE foobar2000 installation: your foobar profile directory is in a folder named "profile" inside your installation directory.

2. Run foobar, choose ColumnUI as user interface (from the prompt, or from File > Preferences > Display)

3. From Columns UI in File > Preferences > Display > Columns UI, click on import, and select the following file: [FOOBAR_PROFILE_DIRECTORY]\themes\eole\columnsUI_eole.fcl.

4. Optionally, if you want an extra polish, change the systray icon: Click the Foobar button on top > File > Preferences > Display > Columns UI > On the right, notification area tab > Tick Use custom icon > Click Select icon... and select the file [FOOBAR_PROFILE_DIRECTORY]\themes\eole\img\systray icons\white\uniEC4F.ico (or any of the alternative icons in this folder)

That's it! Enjoy your sound.

## Useful to know

- Eole uses a cover cache. The cover cache is built little by little: when a cover is displayed, if it isn't stored yet in the cache, it will be added to it, so on first display of any cover, it will be a little bit slow, but it will get a lot faster on the second display. This cache is based on the %album artist% & %album% tags. After updating a existing cover, you must manually refresh it in foobar, do a right click over the cover which need to be refreshed, and you will have a menu item for that.

- The library browser panel have an option to load every covers from the image cache at startup which is enabled by default and allow to browse your library without waiting for the covers to load. Foobar memory usage is higher when this option is enabled, because all the covers are loaded into the memory. This option works only once the image cache is already built: the image cache is built little by little: when a cover is displayed, if it isn't stored yet in the cache, it will be added to the cache.

- Most panels have a settings menu, do a right click over them for that, or look for the hamburger icons. And if you want to get your hands dirty and edit a panel, press SHIFT and do a right click, you will then have a configure option, and you will see from the code which file contains the related script.

## Credits
- [TheQwertiest](https://github.com/TheQwertiest): Spider Monkey Panel, which powers most of this theme [foo_spider_monkey_panel](https://github.com/TheQwertiest/foo_spider_monkey_panel)
- [marc2003](https://github.com/marc2k3): original [foo_jscript_panel](https://github.com/marc2k3/foo_jscript_panel)
- [T.P. Wang](https://hydrogenaud.io/index.php?action=profile;u=44175): original [WSH Panel Mod](https://code.google.com/archive/p/foo-wsh-panel-mod).
- [Br3tt aka Falstaff](https://www.deviantart.com/br3tt): original code for most of the panels
- [WilB](https://hydrogenaud.io/index.php?action=profile;u=33113): original code of the library tree panel, and biography panel
