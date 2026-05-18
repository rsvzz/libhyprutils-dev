# how to use this repo
## hyprutils-dev is library of hyprutils
### this library is for hyprland (=>0.55) 
# Get Ubuntu 26.04 LTS
[![Get it Launchpad](https://launchpadlibrarian.net/606381979/CoF%2064px.png)](https://launchpad.net/~rsvzz/+archive/ubuntu/libhyprutils-dev)

## Install PPA

    sudo add-apt-repository ppa:rsvzz/libhyprutils-dev
    sudo apt update
    sudo apt install libhyprutils-dev

### Create .deb of libhyprutils-dev https://github.com/hyprwm/hyprutils.git manual use this repo

    uscan --verbose --download-current-version --force-download
    tar -xf ../hyprutils-dev-0.13.1.tar.gz //changed for new version
    cp -r debian hyprutils-dev-0.13.1  //changed for new version
    debuild -us -uc // generate .deb

### install
    sudo dpkg -i ../hyprutils-dev-version.deb
    sudo apt remove hyprutils-dev

### Finished running lintian.
  
