# OS X Installation Disk Image Creation Script

## Overview
For you who prefer an optical installation disk to a USB installation media

## Description
You can make an OS X installation image from an app file which can be got from App Store.

## Supported Installation Packages
* Install OS X Mavericks.app
* Install OS X Yosemite.app
* Install OS X El Capitan.app
* Install macOS Sierra.app
* Install macOS High Sierra.app
* Install macOS Mojave.app (to be verified)

Maybe this script can be executed with the below packages:
* Install Mac OS X Lion.app
* Install OS X Mountain Lion.app

## Usage
1. Deploy this script at any folder
2. Deploy "Install *os-name*.app" at the same folder
3. Grant execute permission
4. Execute this script
5. Select OS X version
6. Wait for a while
7. Generate installation DMG and ISO files (and burn it on a DVD+/-R DL, DVD+/-RW DL, BD-R, or BD-RE blank media with Disk Utility)

OS X Terminal:

    $ cd ~/Desktop
    $ git clone --depth 1 https://github.com/gcch/OS-X-Installation-Disk-Image-Creation-Script.git ./dsk-img-creator
    $ cd dsk-img-creator
    $ chmod +x os-x-inst-dsk-img-creation-script.command
    $ cp "/Applications/Install <os-name>.app" ./
    $ ./os-x-inst-dsk-img-creation-script.command

## Verification Environment
* iMac (21.5-inch, Mid 2011)
  * Support OS: OS X Lion (10.7) - macOS High Sierra (10.13.6)

## License
This script is released under the MIT license. See the LICENSE file.

## Author
* tag (Twitter: [@tag_ism](https://twitter.com/tag_ism "tag (@tag_ism) | Twitter") / Blog: http://karat5i.blogspot.jp/)
