# how to use this repo
### Create .deb of lib https://github.com/hyprwm/hyprutils.git

    uscan --verbose --download-current-version --force-download
    tar -xf ../hyprutils-dev-0.13.1.tar.gz //changed for new version
    cp -r debian hyprutils-dev-0.13.1  //changed for new version
    debuild -us -uc // generate .deb

### install
    sudo dpkg -i ../hyprutils-dev-version.deb
    sudo apt remove hyprutils-dev

### Finished running lintian.

## this repo public PPA comming soon for ubuntu 26.04 LTC
  
