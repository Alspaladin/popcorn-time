#Popcorn time
Personnal Popcorn-Time repo


### Install a release with automated script : 

    wget https://raw.githubusercontent.com/MrVaykadji/popcorn-time/master/install-release -O install-popcorn
    bash install-popcorn
    rm install-popcorn
    
### Build from sources with automated script : 

    wget https://raw.githubusercontent.com/MrVaykadji/popcorn-time/master/popcorn-build
    bash popcorn-build
    rm popcorn-build

### Uninstall : 

    bash /opt/popcorn-time/uninstall

----------------

### Idea

To allow any computer user to watch movies easily streaming from torrents, without any particular knowledge. 

#### Error "Gtk-WARNING **: cannot open display:"
Try running `export DISPLAY=:0.0`

#### Error "The video format is not supported"
See: https://github.com/rogerwang/node-webkit/wiki/Support-mp3-and-h264-in-video-and-audio-tag
