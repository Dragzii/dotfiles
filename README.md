# dotfiles
My personal configuration files for the desktop I am currently using. I configured the following programs:
- bspwm (window manager/desktop environment) https://github.com/baskerville/bspwm
- sxhkd (custom keybinds for bspwm that execute a command on input) https://github.com/baskerville/sxhkd
- polybar (custom status bar) https://github.com/polybar/polybar
- alacritty (terminal/terminal emulator that is configured through YAML) https://github.com/alacritty/alacritty
- mopidy (local music playing/streaming server) https://github.com/mopidy/mopidy
- ncmpcpp (terminal music player that interfaces with mopidy to stream music from Google Play Music to my computer) https://github.com/arybczak/ncmpcpp
- Xresources (color/font configuration files for the old terminal I used, urxvt) https://github.com/exg/rxvt-unicode
- zsh (the terminal shell I use in alacritty) https://www.zsh.org/

# How these work
Most of these files are what is called the .ini format, which is a standard format for configuration files for most programs. It consists of two simple elements: properties and modules.
Modules define sections of the configuration files, and points the program to different properties for that section. <br />
![Image of Module](http://natec.me/2020-03-26_13-03.png) <br />
<br />
Properties are simple lines that tell the program to recognize a property inside the program as a specific value, such as a string of text, a color, or a reference to another module. <br />
![Image of Property](http://natec.me/2020-03-26_13-10.png)
# Screenshots
![Image of Desktop](http://natec.me/Screenshot1.png)
