# July

## About

A simple theme for the ZSH shell.

Here is preview that you can check out:

![](preview.png)

Note: the colors used in this shell theme will depend on your terminal emulator's theme. This means that it may look different in your setup compared to the preview. Theme used is [Flamerial](https://github.com/skippyr/flamerial).

In the prompt, you will find:

- Your host and user name.
- Your current directory path.

## Installation

### Dependencies

In order to install and run this software properly, the following dependencies must be installed:

- `git`: required to clone this repository.

### Procedures

Using a command-line utility, follow these steps:

- Clone this repository using `git`.

```bash
git\
    clone --depth 1 https://github.com/skippyr/july\
    ~/.local/share/zsh/themes/july
```

- Add the following source rule to your `~/.zshrc` file. Ensure to not source any other theme to avoid causing conflicts.

```bash
source ~/.local/share/zsh/themes/july/july.zsh-theme
```

- Reopen your shell session. At this point, the theme should be installed and running.

## Support

Report issues, questions and suggestions through its [issues page](https://github.com/skippyr/july/issues).

## Copyright

This software is under the MIT license. A copy of the license is bundled with the source code.
