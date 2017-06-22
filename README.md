# roblesnotes
My own personal webpage

## install hugo

    apt-get install golang -y
    wget https://github.com/gohugoio/hugo/releases/download/v0.23/hugo_0.23_Linux-64bit.deb
    sudo dpkg -i hugo_0.23_Linux-64bit.deb

## deploy

    git clone https://github.com/Findeton/roblesnotes.git
    cd roblesnotes/themes
    git clone https://github.com/shenoybr/hugo-goa.git
    cd ..
    hugo -v

## test

    hugo server --theme=hugo-goa