Spectools is (c) 2007-10 Michael Kershaw/Dragorn <dragorn@kismetwireless.net>
Licensed under GPL

Please refer to file "README" for the full Kismet Wireless Spectrum Tools readme.

This patched version adds support to the DSRC channels in the 5.9 GHz band, for Wi-Spy DBx devices only, at the moment, and enables the selection of the power range (minimum and maximum dBm values) to be displayed in the GUI, for any device.

**How to download and compile under Linux**
* If not yet installed, install "libusb-dev" (the command which is shown below is related to Debian and "apt-get"):
```
sudo apt-get install libusb-dev
```
* You also need GTK+ to be installed in order to compile the GUI. Please refer to the GTK website or, to install version 2.0 under Debian, use:
```
sudo apt-get install libgtk2.0-dev
```
* Clone this repository:
```
git clone https://github.com/francescoraves483/spectools-dsrc.git
```
* Prepare the source code:
```
cd spectools-dsrc
./configure
```
* Compile:
```
make
```

The GUI can then be launched using:
```
./spectool_gtk
```