# July

## Starting Point

The July project is a minimalist theme for the ZSH shell inspired by the default
theme for Bash in Ubuntu and Arch Linux.

This theme can be setup with a series of terminal emulators, themes and
wallpapers. You can use following preview as a source of inspiration and
reference to see what it can look like:

![](./images/preview.png)

> In this preview, the July theme was used within the [Kitty terminal emulator](https://github.com/kovidgoyal/kitty)
with the [Flamerial theme](https://github.com/skippyr/flamerial). Font used is
FantasqueSansM Nerd Font. Wallpaper is [Waterfalls during daytime by Ingi Haraldss](https://unsplash.com/photos/XnkK88K2bao) from Unsplash.

## Features

This theme can show you the following information:

* Your user and hostname.
* Your current directory path.

## Installation

You can install this theme in multiple ways, use the one that suits you best.

### Manually

* Run the following command to install the theme at
  `~/.local/share/zsh/themes/july`.

    ```bash
    git clone --depth=1 https://github.com/skippyr/july ~/.local/share/zsh/themes/july &&
    echo "source \"${HOME}/.local/share/zsh/themes/july/july.zsh-theme\"" >> ~/.zshrc
    ```

* Reopen your terminal emulator.

### Within OhMyZSH

* Install the theme in OhMyZSH custom themes' directory.

    ```bash
    git clone --depth=1 https://github.com/skippyr/july ${ZSH_CUSTOM:-${HOME}/.oh-my-zsh/custom}/themes/july
    ```

* Change the value of the `ZSH_THEME` variable in your ZSH configuration file,
  `~/.zshrc`, to use the theme.

    ```bash
    ZSH_THEME="july/july"
    ```

* Reopen your terminal emulator.

## Issues And Contributions

Learn how to report issues and contribute to this project by reading its
[contributions guidelines](https://skippyr.github.io/materials/pages/contributions_guidelines.html).

## License

This project is released under the terms of the MIT license. A copy of the
license is bundled with the source code.

Copyright (c) 2023, Sherman Rofeman. MIT license.
