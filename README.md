VIM as IDE
==========

Options and plugin collections from my VIM as IDE

Clone this repository in your .vim directory

``` bash
cd $HOME/.vim
git clone https://github.com/felipedjinn/vim.git .
```

Add the follow ine at the end of /etc/vimrc file

``` bash
" Load user vim configuration file if exists
if filereadable($HOME . "/.vim/vimrc.local")
      exec "source " . $HOME . "/.vim/vimrc.local"
endif
```
