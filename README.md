#Gnome-Shell Extension Audio-Output-Switcher

![The menu](https://extensions.gnome.org/static/extension-data/screenshots/screenshot_1028.png)

## About

This extension adds a little entry to the status-menu that shows the currently
selected pulse-audio-output device. Clicking on that will open a submenu with
all available output devices and let's you choose which one to use.

This extension is based on anducs work at https://github.com/anduchs/audio-output-switcher but it's not supported on last version of gnome-shell

Most importantly this extension is a s simple as possible. Therefore it does not
include an imput switcher or similar.
See Audio-Input-Switcher (https://github.com/anduchs/audio-input-switcher)
extension for microphone selection.

## Installation


Either via 

    https://extensions.gnome.org/extension/1028/gnome-shell-audio-output-switcher/

or via git

    git clone git@github.com:kgaut/gnome-shell-audio-output-switcher.git ~/.local/share/gnome-shell/extensions/gnome-shell-audio-output-switcher@kgaut

Then restart the gnome-shell via CTRL+F2 r and enable the extension using gnome-tweak-tool

To update later, just issue

    (cd ~/.local/share/gnome-shell/extensions/gnome-shell-audio-output-switcher@kgaut && git pull)
