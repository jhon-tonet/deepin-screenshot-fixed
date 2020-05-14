# Deepin Screenshot Copy to Clipboard function fixed!

The correction was maded based on https://github.com/linuxdeepin/deepin-screenshot/ version but how this repository was archived, I create this new to share this.<br /><br />

The code was extracted from https://gist.github.com/msenol86/c0c7daad3de32a7922486e5d669f24c6 arch solution that consists in change mainwindow.cpp file.

## So, download it and:
create a build folder <br />
inside build folder run: <br />
cmake ../ <br />
make <br />
make install<br />

## Dependencies 
sudo apt-get install debhelper cmake qt5-default qtbase5-dev pkg-config libqt5svg5-dev libqt5x11extras5-dev qttools5-dev-tools libxcb-util0-dev libstartup-notification0-dev qtbase5-private-dev qtmultimedia5-dev x11proto-xext-dev libmtdev-dev libegl1-mesa-dev x11proto-record-dev libxtst-dev libudev-dev libfontconfig1-dev libfreetype6-dev libglib2.0-dev libxrender-dev libdtkwidget-dev libdtkwm-dev deepin-gettext-tools xclip

After install you can put this application on gnome main menu copying the files to these following directiories (ubuntu): <br />
/usr/bin/deepin-screenshot (file exec) <br />
/usr/share/deepin-screenshot (folder) <br />
/usr/share/deepin-screenshot/image/deepin-screenshot.svg (icon - needs permission) <br />
/usr/share/applications/deepin-screenshot.desktop (menu app) <br />
