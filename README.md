# bubblelights

A colortheme for vim based on [bubblegum] and [southernlights].

![Screenshot](images/screenshot.png)

[bubblegum]: https://github.com/baskerville/bubblegum
[southernlights]: https://github.com/jalvesaq/southernlights


## Installation

Use a plugin manager of your choice to install it ([Pathogen], [Vundle], ...),
or simple copy `bubblelighgts.vim` into `~/.vimrc/colors`:

```bash
wget https://github.com/hagenw/bubblelights/raw/master/colors/bubblelights.vim \
     -O ~/.vimrc/colors/bubblelights.vim
```

[Pathogen]: (https://github.com/tpope/vim-pathogen)
[Vundle]: (https://github.com/VundleVim/Vundle.vim)

Then enable the colorscheme in your `~/.vimrc` with the following command:
`colorscheme bubblelights`.

If you only use GVim, you're done! If you use terminal Vim, read on...

Bubblelights supports 256 color terminals, but it makes use of redefinitions of
the basic terminal colors to get some additional colors.  Open your `~/.vimrc`
with Vim in your terminal and try `:set termguicolors`. If colors are rendered
properly, you can add this command in your `~/.vimrc`.  If not, configure your
terminal emulator to use the color palette given below.

## Terminal color palette

![Palette](images/palette.png)

| colors                                | cterm | gui     |
|:-------------------------------------:|:-----:|:-------:|
| ![color0](images/colors/color0.png)   | 0     | #454545 |
| ![color1](images/colors/color1.png)   | 1     | #dca3a3 |
| ![color2](images/colors/color2.png)   | 2     | #afc5af |
| ![color3](images/colors/color3.png)   | 3     | #ffffef |
| ![color4](images/colors/color4.png)   | 4     | #9eaa00 |
| ![color5](images/colors/color5.png)   | 5     | #cdbfaf |
| ![color6](images/colors/color6.png)   | 6     | #a1b5cd |
| ![color7](images/colors/color7.png)   | 7     | #dedede |
| ![color8](images/colors/color8.png)   | 8     | #71a3b7 |
| ![color9](images/colors/color9.png)   | 9     | #f4a45f |
| ![color10](images/colors/color10.png) | 10    | #95c749 |
| ![color11](images/colors/color11.png) | 11    | #cdcdc1 |
| ![color12](images/colors/color12.png) | 12    | #1cc7c9 |
| ![color13](images/colors/color13.png) | 13    | #cdbfaf |
| ![color14](images/colors/color14.png) | 14    | #a1b5cd |
| ![color15](images/colors/color15.png) | 15    | #dedede |
| ![fg](images/colors/color-fg.png)     | fg    | #d1d1d1 |
| ![bg](images/colors/color-bg.png)     | bg    | #454545 |

## Plugins support

Bubblelights provides color definitions for the following plugins:

* [Buftabline](https://github.com/ap/vim-buftabline)
