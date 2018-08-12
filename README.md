# Tmux Config

Rukbotto's tmux configuration files.

## Installation

Clone this repo in your home folder:

```
$ git clone https://github.com/rukbotto/tmux-config.git ~/.tmux-config
```

## Usage

Link the `tmux.conf` file to your home folder:

```
$ ln -svf ~/.tmux-config/tmux.conf ~/.tmux.conf
```

Finally, create a `.local.tmux.conf` file in your home folder:

```
$ touch ~/.local.tmux.conf
```

## MacOS settings

First you need to install the `reattach-to-user-namespace` package:

```
$ brew install reattach-to-user-namespace
```

To enable MacOS settings, source the file `macos.tmux.conf` in your local config file:

```
source-file "${HOME}/.tmux-config/macos.tmux.conf"
```

## Color schemes

This config enables 256 color support and provides a color scheme called cyanide. To use it, source the file `cyanide.tmux.conf` in your local config file:

```
source-file "${HOME}/.tmux-config/colors/cyanide.tmux.conf"
```
