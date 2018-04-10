# NO RELEASES AVAILABLE JUST YET
If you somehow stumbled across this by accident, I am currently writing the readme ahead of actual builds being available. If this paragraph is here then there's nothing to see on the repo right now. Sorry come back soon.

# TILTED

The **Tilted** application suite is an arcade-style gaming front-end system, library management solution, and media server for emulators and PC games.  Tilted offers an unprecedented level of user convenience never before seen in other front-ends, while at the same time providing the most powerful features and remaining fully customizable.

Tilted is primarily intended for gaming PCs with modern graphics cards. This is especially ture if you have a custom-built arcade cabinet.  While the classics are fantastic, there are also **hundreds** of amazing arcade-friendly games released for the PC every year. Many of them are true masterpieces, and none of them will run on a $25 embeded kit. For all the time, money and effort used to build or aquire an arcade cab, you owe it to yourself to power it with a real gaming rig, and Tilted is the best front-end solution for it.

## Core Components
- **Tilted Agent - Beta Available Now**. The workhorse. The backbone. This lightweight app runs silently in the system tray of the PC you play your games on. It automatically detects and responds to any changes in your roms, media, and Steam libraries. It includes an easy-to-use web API for simple access to all of your data and game media. The Windows build of Tilted Agent 1.0-beta is available now for download in the releases section. The upcoming Tilted Agent 2.0 is open source and hosted here in this repository.  Version 2.0 is multiplatform and will run on Windows, Linux and MacOS with support for Steam and RetroArch on all three platforms.

- **Tilted UI - Coming Very Soon**  This is the actual front-end of the front-end suite.  Built from the ground up using the newest development tools, it takes advantage of the latest and greatest graphics and animation features of Windows 10. It loads in just a few seconds. It runs at a steady 60fps without any lag or screen tearing. It can be run on the same PC as Tilted Agent, or it can be run remotely on another system such as a tablet, offering Second-Screen functionality. The default skin's native resolution is 1440p and looks beautiful at any scale. Tilted UI is optimized for multiple screen shapes and sizes and automatically adjusts the aspect-ratio accordingly using a feature called Visual States.It handles any kind of input including gamepads, arcade sticks, trackballs, spinners, and even multitouch gestures. The Windows 10 release of Tilted UI is fully customizable, and will be followed up with Android and iOS versions at a future date.

## Optional Utilities
- **Tilted Media Tool - Beta Available Now** While Tilted Agent handles basic media integration tasks, Tilted Media Tool offers a more advanced and comprehensive means of obtaining media for your game library with the ability to batch download from various sources (Emumovies, ScreenScraper, TheGamesDb.net, and more). It also batch converts your HyperSpin themes into open, easy-to-tweak HTML5/CSS3 files which can run natively in Tilted UI as animated wallpaper.

- **Tilted Data Tool - Coming Soon**  For advanced users. Each release of Tilted Agent will include a local version of the Tilted Database, a collection of information about practically every video game ever made. Basic game data comes from all of the various game preservation groups such as No-Intro, MAME, and TOSEC, as well as more detailed data from online sources such as thegamesdb.net. However if you want to generate your own database using the latest DAT files or some other sources, you can do so using this tool.

## Features

- Automatic rom detection and library creation.  Point to one or more rom folders you're done. No need to go through a bunch of steps or do one platform at a time.  No need to provide your own database files (unless you want to). If your games are not well named or organized that's not a problem because Tilted Agent will also check hash signitures if need be. None of your files will be moved, copied, deleted or renamed. Instead Tilted creates a user's game library which is tagged with everything about the games such as proper titles, languages, descriptions, etc.

- Intelligent media detection and game matching.  Tilted will check many possible folder and file naming conventions for media and match them appropriately to your games.

- Web API with WebSocket push notifications offers the potential of countless second-screen possibilities such as wireless marquees, live control panels, and digital manuals. This feature is particularly exciting for arcade cabinet builders.

- Smart playlist creation. The games in your collection are logically filtered and displayed so that you don't see multiple versions of the same game while prioitizing your language and locale. Clones and bad dumps are ignored. Various playlist menu schemes are available. Special exception games are easy to make with force include and force exclude options.  You can also provide your own custom playlists with as many sub-menus as you want.

- Supports importing HyperSpin themes and HyperSpin override transitions. Also supports full screen video wallpaper as well as HTML5 animated wallpaper (which in turn may contain many different videos and animations).  Seamlessly transition betwen all wallpaper types and even mix video backgrounds with animated overlays.

- Tilted UI coems with a highly customizable default skin as well as the ability to design and save your own basic skins in the application itself. Skin packages may include custom overlay graphics, sounds, and fonts that require no system installation.  For advanced designers, you can also create a 100% fully customized skin by providing a XAML file. Your advanced skin can still use selected menus and controls of the default skin if you want, or you can replace the entire UI with your own creation.

- RetroArch integration.  Detects which cores you have and uses a lookup table to find the best default core for each platform.  Users can easily override these defaults on a per-platform or even per-game level and tell it to use another core.  Or another emulator.  You can add any external emulator or launcher you want with minimal fuss.  Or you can just use the excellent RocketLauncher application, which is fully supported.

- Steam integration.  Zero setup required.  Even if you don't own any Steam games, non-Steam PC games are launched using the client to provide a clean and reliable way to always detect when the game is running and when it's finished. This way Tilted always knows when to return to the front-end and when not to. There is no need to go through the old granular process of adding new PC games to a front-end.  You don't need to provide file names, window handle names, time delays or anything like that. There is no "Steam Wheel Creator" tool, banners and backgrounds are obtained automatically.  As soon as you install a new PC game (even if done remotely) it will immediately pop up in the UI and be ready to play.

## Authors

* **Sean O**

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the GPLv3 License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to the Avalonia team, whose framework this new open source version of Tilted Agent will likely be based on.
* Thanks to gmatthews, pvroos, lukasf, brolly.
* Special thanks to anyone who created original artwork content for HyperSpin that will hopefully see new life on Tilted.
