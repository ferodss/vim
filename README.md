VIM as IDE
==========

Options and plugin collections from my VIM as IDE

Clone this repository in your .vim directory and update Vundle submodule

``` bash
cd $HOME/.vim
git clone https://github.com/felipedjinn/vim.git .
git submodule init
git submodule update
```

Install bundles

Launch vim and run `:BundleInstall`

To install from command line: `vim +BundleInstall +qall`


Create a symbolic link from ~/.vim/.vimrc to ~/.vimrc

``` bash
ln -s ~/.vim/.vimrc ~/.vimrc
```
