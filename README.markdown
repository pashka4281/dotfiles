This is my ~/.vim folder I use on Macbook Pro.

Installation/Usage
==================

Run the following command from your terminal and enjoy the fireworks!
    brew update
    brew install curl git the_silver_searcher

    curl https://github.com/gduquesnay/dotfiles/blob/master/personal_installer.sh | sh
    git clone https://github.com/gmarik/vundle.git ~/.vim/bundle/vundle
    vim +BundleInstall +qall
