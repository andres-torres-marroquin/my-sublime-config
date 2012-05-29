Installing on Mac OSX:

    cd https://github.com/wbond/sublime_package_control
    rm -rf User "Package Control"
    git clone https://andres-torres-marroquin@github.com/andres-torres-marroquin/my-sublime-config.git User
    git clone https://github.com/wbond/sublime_package_control.git "Package Control"

Installing on Linux: *outdated*

    cd ~/.config/sublime-text-2/Packages/User/
    rm -rf *
    git clone git@github.com:andres-torres-marroquin/my-sublime-config.git .
    git submodule init
    git submodule update
    cd ..
    rm -rf SublimeLinter
    git clone git://github.com/Kronuz/SublimeLinter.git
