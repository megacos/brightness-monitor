# brightness
Changes brightness of all connected monitors in software. This is to be used in the case where `xbacklight` fails. 
It was designed to be bound to keyboard shortcuts.

<img src="https://i.stack.imgur.com/R5wQz.png">


## Example Commands
    brightness 75
    brightness -5
    brightness +10

## Usage
       brightess [n] [+n] [-n]
       n       An integer from 0 to 100 specifies a brightness level.
       +n      Increase brightness by n.
       -n      Decrease brightness by n.
               No argument shows current brightness level.
## Installation

1. wget https://github.com/megacos/brightness-monitor/raw/master/brightness
2. chmod 755 brightness
3. sudo mv brightness /usr/local/bin/ (for system wide) or ~/.local/bin/ (for users, this is my cup of tea because i am single user of my pc)
4. create a shortcut with the above commands

## See also sarmad

I've also written a program called [sarmad](https://github.com/hackerb9/sarmad) which works for external monitors using the built-in brightness keys on laptops. It monitors the brightness of the internal backlight and replicates that. 
