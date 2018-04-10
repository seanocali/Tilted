# Tilted

The **Tilted** application suite is an arcade-style gaming front-end system for emulators and PC games.  Tilted offers an unprecedented level of user convenience never before seen in other front-ends, while at the same time providing the most powerful features and remaining fully customizable.

Tilted is primarily intended for gaming PCs with modern graphics cards. This is especially ture if you have a custom arcade cabinet.  While the classics are fantastic, there are also **hundreds** of amazing arcade-friendly games released for the PC every year. Many of them are true masterpieces, and none of them will run on a $25 embeded kit. For all the time, money and effort used to build or aquire an arcade cab, you owe it to yourself to power it with a real gaming rig.

## Suite
- **Tilted Agent - Beta Available Now**. The workhorse. The backbone. This lightweight app runs silently in the system tray of the PC you play your games on. It automatically detects and responds to any changes in your roms, media, and Steam libraries. It includes an easy-to-use web API for simple access to all of your data and game media. The Windows (7, 8, 10) build of Tilted Agent 1.0-beta is available now for download in the releases section. The upcoming Tilted Agent 2.0 is open source and hosted here in this repository.  Version 2.0 is multiplatform and will run on Windows, Linux and MacOS with support for Steam and RetroArch on all three platforms.

- **Tilted UI - Coming Very Soon**  This is the actual front-end of the front-end suite.  Built from the ground up using the newest development tools, it takes advantage of the latest and greatest graphics and animation features of Windows 10. It can be run on the same PC as Tilted Agent, or it can be run remotely on another system offering Second-Screen functionality.  Tilted UI is optimized for multiple screen shapes and sizes and automatically adjusts accordingly.  It handles any kind of input including gamepads, arcade sticks, trackballs, spinners, and even multitouch gestures.  The Windows 10 release of Tilted UI is fully customizable, and at a future date will be followed up with Android and iOS versions.

- **Tilted Media Tool - Beta Available Now** While Tilted Agent handles basic media integration tasks, Tilted Media Tool offers a more advanced and comprehensive means of obtaining media for your game library with the ability to batch download from various sources (Emumovies, ScreenScraper, TheGamesDb.net, and more). It also batch converts your HyperSpin themes into open, easy-to-tweak HTML5/CSS3 files which can run natively in Tilted UI as animated wallpaper.

- **Tilted Data Tool - Coming Soon**  For advanced users. Each release of Tilted Agent will include a local version of the Tilted Database, a collection of practically every video game ever made. Basic game data comes from all of the various game preservation groups such as No-Intro, MAME, and TOSEC, as well as more detailed data from online sources such as thegamesdb.net. However if you want to generate your own database using the latest DAT files or some other sources, you can do so using this tool.

## Features

- Automatic rom detection and library creation.  Point to one or more rom folders you're done. No need to go through a bunch of steps or do one platform at a time.  No need to provide your own database files (unless you want to). If your games are not well named or organized that's not a problem.  Tilted Agent will also check hash signitures.

- Intelligent media detection and game matching.  Tilted will check many possible folder and file naming conventions for media and match them appropriately to your games.

- Web API with WebSocket push notifications offers the potential of countless second-screen possibilities such as wireless marquees, live control panels, and digital manuals. This feature is particularly exciting for arcade cabinet builders.

- Smart playlist creation. The games in your collection are logically filtered and displayed so that you don't see multiple versions of the same game while prioitizing your language and locale.  Various playlist menu schemes are available. Any game can be force included or force excluded from this algorithm.  You can also provide your own custom playlists with as many sub-menus as you want.

- Supports HyperSpin themes and HyperSpin override transitions. Also supports full screen video wallpaper as well as HTML5 animated wallpaper (which in turn may contain many different videos and animations).  Seamlessly transition betwen all wallpaper types and even mix video backgrounds with animated overlays.

- Tilted UI coems with a highly customizable default skin as well as the ability to design and save your own basic skins in the application itself. Skins packages may include custom overlays, sounds, and fonts that require no system installation.  For advanced designers, you can also create a 100% fully customized skin by providing a XAML file. Your advanced skin can still use selected menus and controls of the default skin if you want, or you can replace the entire UI with your own creation.

- RetroArch integration.  Detects which cores you have and maintains a database of the best default core for each platform.  Users can easily override these defaults on a per-platform or even per-game level and tell it to use another core.  Or another emulator.  You can add any external emulator or launcher you want with minimal fuss.  Or you can use RocketLauncher, which is fully supported.

- Steam integration.  Zero setup required.  Even if you don't own any Steam games, non-Steam PC games are launched using the client to provide a clean and reliable way to always detect when the game is running and when it's finished. This way Tilted always knows when to return to the front-end and when not to. There is no need to go through the granular process of adding new PC games.  No adding .exe names, window handle names, time delays or anything like that.  Even thumbnails and game data are automatically downloaded. Tilted is especially suitable for active gamers who are still buying. 

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you have to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone who's code was used
* Inspiration
* etc
