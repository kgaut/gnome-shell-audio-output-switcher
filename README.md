#Gnome-Shell Extension Audio-Output-Switcher


![The menu](https://extensions.gnome.org/static/extension-data/screenshots/screenshot_1028.png)

## Compatibility
  - Gnome Shell 3.10
  - Gnome Shell 3.12
  - Gnome Shell 3.14
  - Gnome Shell 3.16
  - Gnome Shell 3.18
  - Gnome Shell 3.20

## About

This extension adds a little entry to the status-menu that shows the currently
selected pulse-audio-output device. Clicking on that will open a submenu with
all available output devices and let's you choose which one to use.

This extension is based on anducs work at https://github.com/anduchs/audio-output-switcher but it's not supporting last versions of gnome-shell.

## Installation

Either via

https://extensions.gnome.org/extension/1028/gnome-shell-audio-output-switcher/

or via git

`git clone git@github.com:kgaut/gnome-shell-audio-output-switcher.git ~/.local/share/gnome-shell/extensions/gnome-shell-audio-output-switcher@kgaut`

Then restart the gnome-shell via ALT+F2 r and enable the extension using gnome-tweak-tool

To update later, just issue

`(cd ~/.local/share/gnome-shell/extensions/gnome-shell-audio-output-switcher@kgaut && git pull)`
