Installation:

    git clone git://github.com/dkjer/dottmux.git ~/.tmux

Update submodules:

    pushd ~/.tmux
    git submodule init
    git submodule update
    popd

Create symlinks:

    ln -s .tmux/tmux.conf ~/.tmux.conf

