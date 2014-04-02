#Popcorn time
Personnal Popcorn-Time repo


### Install : 

    wget https://raw.githubusercontent.com/MrVaykadji/popcorn-time/master/install-release -O install-popcorn
    bash install-popcorn
    rm install-popcorn

### Uninstall : 

    bash /opt/popcorn-time/uninstall

----------------

### Idea

To allow any computer user to watch movies easily streaming from torrents, without any particular knowledge. 

## Any problem?

### Error about missing libudev.so.0
Search for libudev.so.0 on your distribution. Most of the time it can be easily fixed by creating a symbolic link from libudev.so to libudev.so.0

See: https://github.com/rogerwang/node-webkit/wiki/The-solution-of-lacking-libudev.so.0

### Error "Gtk-WARNING **: cannot open display:"
Try running `export DISPLAY=:0.0`

### Error "The video format is not supported"
See: https://github.com/rogerwang/node-webkit/wiki/Support-mp3-and-h264-in-video-and-audio-tag
