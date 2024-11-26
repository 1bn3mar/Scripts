# Personal Scripts

These are scripts that i find somewhat helpful and convenient fork/use all you like.

## Overview

The main focus of these scripts is to minimize effort for repetitive tasks or just make my life a little bit faster.

## Scripts Included

- waldl: A script that scrapes for wallpapers that i forked from github.com/pystardust/waldl to make it work in wayland using imv:"as the image viewer" and tofi:"as a rofi replacement".
- paperload: A one liner that simply sets the wallpaper that got downloaded using waldl.
- Read: A two liner that selects a book for me to read in zathura.

## Dependencies

* waldl: `imv`, `tofi`
* paperload: `Hyprland`, `hyprpaper`
* Read: `zathura`, `zathura-pdf-poppler`

## Install

```shell
git clone https://github.com/1bn3mar/Scripts.git && cd Scripts/
sudo stow -t /usr/local/bin
```

## Usage

* waldl: when in `tofi` just input tags from wallhaven seperated by spaces.
* paperload: I set it in my `hyprland.conf` to `exec-once` if i want to change the wallpaper again i just run it in `tofi`.
* move all your'e ebooks to the `directory/` specified in the `$EBOOKS_PATH` variable or just fork it.

## Author

Created by ***@1bn3mar, ibn3mar@icloud.com,*** Unfortunately no website yet.

