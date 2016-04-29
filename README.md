# tabline.vim

Configure tab labels within Terminal Vim with a very succinct output.

![Tabline Screenshot](https://raw.github.com/yfiua/tabline.vim/master/screenshots/tabline.png)

- Tab number
- [+] if the current buffer has been modified
- [Filename] basename only

Tabs in this case, refer to Vim Tabs and not the Terminal.app tabs.

Based on settings found from [offensive
thinking](http://www.offensivethinking.org/data/dotfiles/vimrc).

## Installation
Install using [Vundle](https://github.com/VundleVim/Vundle.vim):

```
Plugin 'yfiua/tabline.vim'
```

## Configuration
Currently there are no configuration variables to define, you either
rock it or you don't. This may change at some point in the future.

Make sure to set the following settings within your color theme: 

```
hi TabLine      ctermfg=Black  ctermbg=Green     cterm=NONE
hi TabLineFill  ctermfg=Black  ctermbg=Green     cterm=NONE
hi TabLineSel   ctermfg=White  ctermbg=DarkBlue  cterm=NONE
```

