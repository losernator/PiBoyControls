# PiBoyControls
Modified PiBoy DMG Controls driver  
original author : Nathan Scherdin  
License : GPL 
PiBoy DMG https://www.experimentalpi.com/
Firmware & script https://www.experimentalpi.com/downloads.html



## Install
```
cd /home/pi
git clone https://github.com/losernator/PiBoyControls.git
cd PiBoyControls
sudo cp -a * /usr/src/xpi_gamecon-1.0/
sudo dkms uninstall -m xpi_gamecon -v 1.0
sudo dkms build -m xpi_gamecon -v 1.0
sudo dkms install -m xpi_gamecon -v 1.0
```
You need to reboot for changes

**Change log** 
change DPAD control to HAT
add bulky deadzone setting to analog stick
