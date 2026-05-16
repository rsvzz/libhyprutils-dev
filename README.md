# how to use
##Create .deb of lib https://github.com/hyprwm/hyprutils.git

  uscan --verbose --download-current-version --force-download
  tar -xf ../hyprutils-dev-0.13.1.tar.gz //changed version current
  cp -r debian hyprutils-dev-0.13.1  //current version
  debuild -us -uc // generate .deb
  
Finished running lintian.
  
