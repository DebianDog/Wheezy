**List of DebianDog-Wheezy fixes found after 04.09.2015:**

**1.** The installer scripts bugs fixing created new problem and the last two versions removed from the repository. 
Recommended to make sure you have this version on your system by reinstalling this package: [debdoginstallscripts_1.0.5_i386.deb](http://smokey01.com/saintless/DebianDog/Packages/Included/debdoginstallscripts_1.0.5_i386.deb)

Or by running in terminal:
```
sudo apt-get update
sudo apt-get remove debdoginstallscripts
sudo apt-get install debdoginstallscripts
```
In case you have some problem with this package check out for updated deb package from Fred [here.](http://murga-linux.com/puppy/viewtopic.php?p=877300&sid=7a08609033f6af763ab2acf4c3941c8c#877300)

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

**4.** Fix for squashfs module loading scripts from Fred. [More information read here.](http://murga-linux.com/puppy/viewtopic.php?p=878996#878996)
```
sudo apt-get update
sudo apt-get install sfsload portablesfs-loadsfs-fuse
```

**5.** Small fix for frisbee. [More information read here.](http://murga-linux.com/puppy/viewtopic.php?p=883158&sid=3588429564754e676ce49df134d930a8#883158)
```
sudo apt-get update
sudo apt-get install frisbee
```

**6.** Small fix for apt2sfs. [More information read here.](http://murga-linux.com/puppy/viewtopic.php?p=885536&sid=e09b92e591e85bcc4632168abdb32e5b#885536)
```
sudo apt-get update
sudo apt-get install apt2sfs
```

**16.** With porteus-boot and only when using save on exit code upgrading libc6 could create some issues. More information and workarownd read [here](http://murga-linux.com/puppy/viewtopic.php?p=889934&sid=00f59036fe7b1df6f8bc7168fe1df597#889934) and the fix [here.](http://murga-linux.com/puppy/viewtopic.php?p=890342&sid=00f59036fe7b1df6f8bc7168fe1df597#890342)
Install this package to fix the problem:
```
sudo apt-get update
sudo apt-get install porteusbootscripts

```
Porteus-boot scripts will be upgraded to new versions with some improvements for save on exit. The changes are not well tested in DebianDog-Wheezy yet. In case you experience some problem you can downgrade the package to the previous version (it has only the fix in snapmergepuppy script for the problem described above and will restore the other scripts to the versions included in the iso):
```
sudo apt-get install porteusbootscripts=0.0.1

```
