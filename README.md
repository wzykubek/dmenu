# dmenu

## Installation
```
sudo make clean install
```

## Added features
* Mouse support
* Line height modify
* .Xresources support
* Hide password (`-P` flag)

## Configuration
#### .Xresources
You can set your colors and font in '~/.Xresources' file and dmenu will use this configuration when you run `xrdb ~/.Xresources`

Avaible '.Xresources' atributes:
* dmenu.font : font or font set
* dmenu.background : normal background color
* dmenu.foreground : normal foreground color
* dmenu.selbackground : selected background color
* dmenu.selforeground : selected foreground color

Example configuration:
```
*.font: Inconsolata:pixelsize=15:antialias=true:autohint=true:hintstyle=hintmedium

*.background: #071616
*.foreground: #dfdfdf

dmenu.selbackground: #144949
dmenu.selforeground: #dfdfdf
```
#### Line height
You can use '-h' argument to set height of dmenu line.
For example:
```
$ dmenu_run -h 24
```
