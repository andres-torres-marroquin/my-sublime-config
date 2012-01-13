Installing on Mac OSX:

    cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User/
    rm -rf *
    git clone git@github.com:andres-torres-marroquin/my-sublime-config.git .
    git submodule init
    git submodule update
    cd ..
    rm -rf SublimeLinter
    git clone git://github.com/Kronuz/SublimeLinter.git

Installing on Linux:

    cd ~/.config/sublime-text-2/Packages/User/
    rm -rf *
    git clone git@github.com:andres-torres-marroquin/my-sublime-config.git .
    git submodule init
    git submodule update
    cd ..
    rm -rf SublimeLinter
    git clone git://github.com/Kronuz/SublimeLinter.git
