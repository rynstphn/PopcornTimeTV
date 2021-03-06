<p align="left " >
  <img src="http://i.imgur.com/76RElTT.png" alt="Popcorn Time" title="Popcorn Time">
</p>

## PopcornTimeTV for iOS & tvOS

[![Platform](http://img.shields.io/badge/platform-iOS%20%7C%20tvOS-lightgrey.svg?style=flat)](https://github.com/Kinglilrowrow)
[![License](https://img.shields.io/badge/license-GPL_v3-373737.svg?style=flat)](https://github.com/Kinglilrowrow/PopcornTimeTV/blob/4.2.0/LICENSE.md)

An ATV, iPhone and iPad application to torrent movies and tv shows for streaming.

## Whats new in this fork (Current Version: 5.0.3)
(Current build tested with iOS 12 on iPhone X, compiled with Xcode 10)

- Apple TV 4K Support
- Xcode 9 support
- Fixes for tvOS and iOS 11
- iPhone X display support (see below for preview)
- Minor improvements
- Fix crash when using search on iOS
- Fix tvOS only searching for TV shows (will display TV & Movie content now)
- Fix freezing after a few seconds of playback (iOS & tvOS)
- Fix memory leaks on tvOS platform causing heavy CPU loads
- Xcode 10 & Swift 4.2 support
- iOS and tvOS 12 support
- Fixes for iOS and tvOS 12
- Support for 2018 iPhones
- Support for 2018 iPads
- Bug fixes and General improvements
- Codebase updates


## To use this project

See NOTICE.md for pods used in this project.

Build instructions (For people new to Git and CocoaPods):

``` bash
$ git clone https://github.com/kinglilrowrow/PopcornTimeTV.git "Save the repo locally"
$ cd PopcornTimeTV/               "Point Terminal to the correct directory"
$ sudo gem install cocoapods      "This only needs to be run once"
$ pod repo update; pod install    "Fetching may take a while, please be patient"
$ open PopcornTime.xcworkspace    "Run this every time you want to compile or make changes"

Profit!

```

## Preview on iPhone X

![PopcornTimeTV](/Preview/iPhoneX-preview.png?raw=true)

## License

If you distribute a copy or make a fork of the project, you have to credit this project as source.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.  If not, see http://www.gnu.org/licenses/.

Note: some dependencies are external libraries, which might be covered by a different license compatible with the GPLv3. They are mentioned in [NOTICE.md](https://github.com/PopcornTimeTV/PopcornTimeTV/blob/master/NOTICE.md).


**This project and the distribution of this project is not illegal, nor does it violate _any_ DMCA laws. The use of this project, however, may be illegal in your area. Check your local laws and regulations regarding the use of torrents to watch potentially copyrighted content. The maintainers of this project do not condone the use of this project for anything illegal, in any state, region, country, or planet. _Please use at your own risk_.**

***


Copyright (c) 2018 Popcorn Time Foundation - Released under the [GPL V3 license](https://github.com/PopcornTimeTV/PopcornTimeTV/LICENSE.md).
