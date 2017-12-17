
Robospin GBA
============

- **Author/Maintainer:** Sean Wallitsch
- **Email:** shidarin@alphamatte.com
- **License:** MIT, CC-BY-NC
- **Status:** Development
- **Version:** 1.0
- **GitHub:** https://github.com/shidarin/robospin_gba

Introduction
------------

[Attract-Mode](http://attractmode.org/about.html) emulator layout based on the
classic robospin theme. Customized for Nintendo Game Boy Advance games.
Classic wheel design showcases snaps or videos in the Game Boy Advance's screen,
as well as showing flyer and cart art.

[![Theme Preview](preview.png?raw=true)](preview.png?raw=true)

[Original photography](https://www.flickr.com/photos/donthomaso84/8411219915/in/photostream/) 
for this theme is by [Thomas Ohlsson Photography](https://www.flickr.com/photos/donthomaso84). 
Retrieved via CC-BY-NC license on December 4th, 2017. Modifications have been 
made to the original work.

Installation
------------

The simplest installation method is through git, from within your attract
mode layout folder::

    git clone https://github.com/shidarin/robospin_gba.git

This will create a `robospin_gba` folder inside your layout folder, and 
you can now select `robospin_gba` as a theme for a display.

You can also unzip archives from the [release page](https://github.com/shidarin/robospin_gba/releases) 
into a `robospin_gba` folder in your layout folder, and it will do the same 
thing without git.

Usage
-----

`robospin_gba` uses a new art type, `cart` to display cartridges besides 
any flyer (box) art. If you wish to display carts, you must create a new 
art entry from the emulator settings window.

Options
-------

`robospin_gba` exposes the following options:

* SpinWheel: The artwork to spin
* Mask: Darkens the area behind the SpinWheel
* Transition Time: Time in milliseconds for wheel spin.

Changelog
---------

*New in version 1.0:*

Initial release.

License
-------

	Code:

	The MIT License (MIT)

	| robospin_gba
	| Copyright (c) 2017 omegaman, verion, raygun, Sean Wallitsch
	| https://github.com/shidarin/robospin_gba

	Permission is hereby granted, free of charge, to any person obtaining a copy
	of this software and associated documentation files (the "Software"), to deal
	in the Software without restriction, including without limitation the rights
	to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
	copies of the Software, and to permit persons to whom the Software is
	furnished to do so, subject to the following conditions:

	The above copyright notice and this permission notice shall be included in all
	copies or substantial portions of the Software.

	THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
	IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
	FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
	AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
	LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
	OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
	SOFTWARE.

	Images:

	Original photography by Thomas Ohlsson Photography
	https://www.flickr.com/photos/donthomaso84/8411219915/in/photostream/
	https://www.flickr.com/photos/donthomaso84
	Distributed under a CC-BY-NC License on December 4th, 2017.
	Modifications have been made.

	Images present in this package are distributed under a CC-BY-NC license
	Note that this is a more restrictive license than the MIT license, and only
	applies to the images.
	http://creativecommons.org/licenses/by-nc/4.0/
	http://creativecommons.org/licenses/by-nc/4.0/legalcode
