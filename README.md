# Vim-Plug
use Vim-Plug to install plugins.
https://github.com/junegunn/vim-plug?tab=readme-ov-file

```
cp ./.vimrc ~/.vim/.vimrc # copy & override config(better backup first)
curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vima # install Vim-Plug
vim  # open vim
:PlugInstall # type that in command mode, install will be started.
```


Reference:
https://github.com/junegunn/vim-plug/issues/812
