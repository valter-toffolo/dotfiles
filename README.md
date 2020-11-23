# dotfiles


## on a new machine:

    git clone --bare https://github.com/valter-toffolo/dotfiles.git $HOME/.dotfiles
    git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME checkout
    bash $HOME/bin/dotfiles-install.sh

- dotfiles-install.sh will create a `dotfiles` alias, so further git management can be done with a simple `dotfiles push` command.

