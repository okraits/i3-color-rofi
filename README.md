## i3-color-rofi

#### Color rofi similar to your i3 wm

### Overview

Fetches the current i3 wm colors and provides an options string to color
[rofi](https://github.com/DaveDavenport/rofi)

### Requirements

i3-color-rofi has the following requirements:

- Python 2 or 3

### Usage

Append it to your [rofi](https://github.com/DaveDavenport/rofi) command line:

    rofi <your-options> $(i3-color-rofi)

i3-color-rofi generates an options string, for example:

    -bg #222222 -fg #888888 -hlbg #285577 -hlfg #ffffff

So your resulting command line may be:

    rofi -rnow -bg #222222 -fg #888888 -hlbg #285577 -hlfg #ffffff

### Installation

Place *i3-color-rofi* anywhere in your $PATH, for example in
*/home/yourUserName/bin*, and ensure that it is executable. Set the path
to the i3 config file in the script. Use it.

### License

This software is released under the terms of the
GNU General Public License v2:

[http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt](http://www.gnu.org/licenses/old-licenses/gpl-2.0.txt)
