**List of DebianDog-Wheezy fixes found after 04.09.2015:**

**1.** Fixes for frugal installer from Fred described [here.](http://murga-linux.com/puppy/viewtopic.php?p=867572#867572) Upgrade the installer package with:
```
sudo apt-get update
sudo apt-get install debdoginstallscripts
```

**2.** Jwm version has xdm login manager included but it doesn't work well in OpenBox.
In OpenBox version you can install this [slim](http://smokey01.com/saintless/DebianDog/Packages/Extra/slim_1.3.4-2-ddwheezy_i386.deb) package.
You can stop/start it from System -> Start/Stop Slim display-manager. More information read [here.](http://murga-linux.com/puppy/viewtopic.php?p=869164#869164) Available also in debiandog-repository:
```
sudo apt-get update
sudo apt-get install slim
```
**3.** Some fixes from Fred for fixdepinstall (install deb and dependencies right click option).
[More information read here.](http://murga-linux.com/puppy/viewtopic.php?p=871384#871384)
Install fixed version from the link above or from terminal:
```
sudo apt-get update
sudo apt-get install fixdepinstall
```
