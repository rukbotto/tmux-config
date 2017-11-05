# Tmux Config

Rukbotto's tmux configuration files.

## Installation

Clone this repo in your home directory:

```
$ git clone https://github.com/rukbotto/tmux-config.git ~/.tmux-config
```

## Usage

Link `.tmux.conf` file to your home directory:

```
$ ln -svf ~/.tmux-config/.tmux.conf ~/.tmux.conf
```

Create a `.tmux.local` file so you can set up your favorite theme, or
otherwise, overwrite the default configuration:

```
$ touch ~/.tmux.local
$ vim ~/.tmux.local
```

## Themes

The `.tmux.conf` file included in this repo enables 256 color support.

This repo currently ships with a single color scheme called
`Base2Tone_SpaceDark`, which is based on [Base2Tone_SpaceDark][1] color scheme
for Vim. It's not set by default, but if you want to give it a try, place the
following lines in your `.tmux.local` file:

```
source-file "${HOME}/.tmux-config/themes/Base2Tone_SpaceDark.tmuxtheme"
```

## Credits

+ [Braam de Haan][2] for authoring [Base2Tone_SpaceDark][1] color scheme for Vim.

[1]: https://github.com/atelierbram/Base2Tone-vim
[2]: https://github.com/atelierbram/
