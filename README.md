# Joseph Ku's Dotfiles

## Installation

    git clone git://github.com/JosephKu/dotfiles ~/.dotfiles
    cd ~/.dotfiles
    rake install


## Installation by rcm

    git clone git://github.com/JosephKu/dotfiles ~/.dotfiles
    RCRC=$HOME/.dotfiles/rcrc rcup


## Track Joseph Ku's Dotfiles

One time:

    git remote add upstream git@github.com:josephku/dotfiles.git
    git fetch upstream
    git checkout -b upstream upstream/master


## Update

Each time you want to update:

    git checkout upstream
    git pull
    git checkout master
    git rebase upstream

