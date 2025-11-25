One day I will add a Openbox desktop setup insired Wayland desktop built on labwc here

Don't forget to setup keyboard after Debian minimal install:
```
sudo apt install console-setup keyboard-configuration
```
Regenerate the keyboard config file
```
sudo dpkg-reconfigure keyboard-configuration
sudo setupcon --force
```
Check your locale
```
locale
```
