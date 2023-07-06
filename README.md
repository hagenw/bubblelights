# bubblelights

A colortheme for vim based on [bubblegum] and [southernlights].

![Screenshot](images/screenshot.png)

[bubblegum]: https://github.com/baskerville/bubblegum
[southernlights]: https://github.com/jalvesaq/southernlights


## Installation

Add it as a package to vim
(see `:help packages`)
with:

```bash
mkdir -p ~/.vim/pack/colors/opt/bubblelights/colors/
wget https://github.com/hagenw/bubblelights/raw/main/colors/bubblelights.vim \
     -O ~/.vim/pack/colors/opt/bubblelights/colors/bubblelights.vim
```

Then enable the colorscheme in your `~/.vimrc` with the following command:

```vim
colorscheme bubblelights
```

If you only use GVim, you're done! If you use terminal Vim, read on...

Bubblelights supports 256 color terminals, but it makes use of redefinitions of
the basic terminal colors to get some additional colors.  Open your `~/.vimrc`
with Vim in your terminal and try `:set termguicolors`. If colors are rendered
properly, you can add this command in your `~/.vimrc`.  If not, configure your
terminal emulator to use the color palette given below.

## Terminal color palette

![Palette](images/palette.png)

| colors                         | cterm | gui     |   | colors                         | cterm | gui     |
|:------------------------------:|:-----:|:-------:|---|:------------------------------:|:-----:|:-------:|
| ![color0](images/color0.png)   | 0     | #454545 |   | ![color8](images/color8.png)   | 8     | #71a3b7 |
| ![color1](images/color1.png)   | 1     | #dca3a3 |   | ![color9](images/color9.png)   | 9     | #f4a45f |
| ![color2](images/color2.png)   | 2     | #afc5af |   | ![color10](images/color10.png) | 10    | #95c749 |
| ![color3](images/color3.png)   | 3     | #ffffef |   | ![color11](images/color11.png) | 11    | #cdcdc1 |
| ![color4](images/color4.png)   | 4     | #9eaa00 |   | ![color12](images/color12.png) | 12    | #1cc7c9 |
| ![color5](images/color5.png)   | 5     | #cdbfaf |   | ![color13](images/color13.png) | 13    | #cdbfaf |
| ![color6](images/color6.png)   | 6     | #a1b5cd |   | ![color14](images/color14.png) | 14    | #a1b5cd |
| ![color7](images/color7.png)   | 7     | #dedede |   | ![color15](images/color15.png) | 15    | #dedede |
|                                |       |         |   |                                |       |         |
| ![fg](images/color-fg.png)     | fg    | #d1d1d1 |   | ![bg](images/color-bg.png)     | bg    | #454545 |


## Plugins support

Bubblelights provides color definitions for the following plugins:

* [Buftabline](https://github.com/ap/vim-buftabline)
* [ctrlp](https://github.com/ctrlpvim/ctrlp.vim)
