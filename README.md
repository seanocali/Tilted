# ![Tilted](https://i.imgur.com/ojqXTsd.png)

The **Tilted** application suite is an arcade-style gaming front-end, library management solution, and media server for emulators and PC games.  Tilted offers an unprecedented level of user convenience never before seen in other front-ends, while at the same time providing the most powerful features and remaining fully customizable.

Tilted is primarily intended for gaming PCs with modern graphics cards. While retro classics are fantastic, there are also hundreds of amazing arcade-friendly games released for the PC every year. Many are true masterpieces, and hardly any of them will run on an embedded platform. For all the time, money and effort used to build or purchase an arcade cabinet, you owe it to yourself to power it with a real gaming rig, and Tilted is the best front-end solution for this.

[Downloads](https://github.com/seanocali/Tilted/releases)

[Documentation](https://github.com/seanocali/Tilted/wiki)

## Core Components
- **Tilted Agent - Beta Available Now**. The backbone and central hub for your games and media. This app runs silently in the system tray of the PC you play your games on. It automatically detects and responds to any changes in your roms, media, and Steam libraries. It provides an easy-to-use web API for simple access to all of your data and game media. The Windows build of Tilted Agent 1.0-beta is available now for download in the releases section. The upcoming Tilted Agent 2.0 is open source and hosted here in this repository.  Version 2.0 is multiplatform and will run on Windows, Linux and MacOS with support for Steam and RetroArch on all three platforms.

- **Tilted UI - Coming Very Soon**  This is the actual front-end of the Tilted app suite.  Built from the ground up using the newest development tools, it takes advantage of the latest and greatest graphics and animation features of Windows 10. It loads in just a few seconds and displays a steady 60fps without any lag or screen tearing. It can be run on the same PC as Tilted Agent, or it can be run remotely on another system such as a tablet, offering second-screen functionality
  The default skin's native resolution is 1440p and looks beautiful at any scale. Tilted UI automatically adjusts the aspect-ratio accordingly using a feature called Visual States. It handles any kind of input including keyboard, gamepad, arcade stick, trackball, spinner, and even touchscreen gestures. The Windows 10 release of Tilted UI is fully customizable, and will be followed up with Android and iOS versions at a future date.

## Optional Utilities
- **Tilted Media Tool - Coming Soon** While Tilted Agent handles basic media integration tasks, Tilted Media Tool offers a more advanced and comprehensive means of obtaining media for your game library with the ability to batch download from various sources (Emumovies, ScreenScraper, TheGamesDb.net, and more). It also batch converts your HyperSpin themes into open, easy-to-tweak HTML5/CSS3 files which can run natively in Tilted UI as animated wallpaper.

## Features

- Automatic rom detection and library creation.  Point to one or more rom folders you're done. No need to go through a bunch of steps or do one platform at a time.  No need to provide your own database files (unless you want to). If your games are not well named or organized that's not a problem because Tilted Agent will also check hash signatures if need be. None of your files will be moved, copied, deleted or renamed. Instead Tilted creates a user's game library which is tagged with everything about the games such as proper titles, languages, descriptions, etc.

- Intelligent media detection and game matching.  Tilted will check many possible folder and file naming conventions for media and match them appropriately to your games.

- Web API with WebSocket push notifications offers the potential for countless second-screen possibilities such as wireless marquees, live control panels, and digital manuals. This feature is particularly exciting for arcade cabinet builders.

- Smart playlist creation. The games in your collection can be logically filtered and displayed so that you don't see multiple versions of the same game while prioritizing your language and locale. Clones, bad dumbs, and older versions can be automatically hidden from the UI. Various playlist menu schemes are available. Special exception games are easy to make with force include and force exclude options.  You can also provide your own custom playlists with as many sub-menus as you want.

- Supports importing HyperSpin themes and HyperSpin override transitions. Also supports full screen video wallpaper as well as HTML5 animated wallpaper (which in turn may contain many different videos and animations).  Seamlessly transition between all wallpaper types and even mix video backgrounds with animated overlays.

- Tilted UI comes with a highly customizable default skin as well as the ability to design and save your own basic skins in the application itself. Skin packages may include custom overlay graphics, sounds.  A skin may also include custom fonts and the user is not required to install them.  For advanced designers, you can also create a 100% fully customized skin by providing XAML files.  Simply tweak the default skin, or re-write the entire UI. The choice is yours.

- RetroArch integration.  Detects which cores you have and uses a lookup table to find the best default core for each platform.  Users can easily override these defaults on a per-platform or even per-game basis.  Additional non-RetroArch emulators or launchers can also be added with minimal fuss.  Or you can just use the excellent RocketLauncher application, which is fully supported.

- Steam integration.  Zero setup required.  Even if you don't own any Steam games, all PC games are launched using the Steam client. This provides a clean and reliable way to always detect when the game is running and when it's finished. This way Tilted always knows when to return to the front-end and when not to. There is no need to go through the old granular process of adding new PC games to a front-end.  You don't need to provide file names, window handle names, custom exit commands, time delays or anything like that. There is no "Steam Wheel Creator" tool--banners and background graphics are obtained automatically.  As soon as you install a new PC game (even if done remotely) it will immediately pop up in the UI and be ready to play.

## License

Tilted Agent 2.0 will be open source and licensed under the GPLv3 License - see the [LICENSE.md](LICENSE.md) file for details.  Tilted Agent 1.0 is not open source but is free to download.


