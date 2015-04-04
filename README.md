# DebianDog Wheezy 

Versions available: jwm_icewm and openbox_xfce

Click here for new packages and fixes information and download links:

http://murga-linux.com/puppy/viewtopic.php?p=776368#776368

Edit: 02.02.2015 - Both DebianDog iso replaced with new versions. List of changes read here.

http://www.murga-linux.com/puppy/viewtopic.php?p=825679#825679

Edit: 14.10.2014 - Both DebianDog iso replaced with new versions. List of changes read here.

http://www.murga-linux.com/puppy/viewtopic.php?p=803595#803595

Edit: 11.08.2014: New version Porteus-Wheezy-3.13.6-openbox.iso with systemd boot enabled, kernel 3.13.6 from Porteus and modules extension changed to .xzm (like in Porteus).
Mirror link + old versions.

Related links:
Infinality fonts packages for Debian Wheezy (thanks to Keisha)
DebianDog wireless LAN HowTo thread
DebianDog HowTo thread
DebianDog Utilities thread
DebianDog Packages section
Setting up Chinese fonts github wiki from limelime
Using kernel 3.14-pae with DebianDog instruction by Keisha
Systemd boot information
Install Spotify on Debian/DebianDog
DebianDog + Blue Pup Quirky Tahr Dual Boot USB Stick How-To
How To Make A Network Storage NAS Appliance With DebianDog and OpenMediaVault
DebianDog-Jessie-OpenBox-Test.iso
DebianDog-SID-Test.iso (Unstable Debian) version - testing.
DebianDog-Squeeze.iso version for old computers
Use old Skype version after 01.08.2014

Edit: 23.07.2014 - DebianDog changed to stable version. List of changes you can find here.

Edit: 16.06.2014 - Both DebianDog iso replaced with new versions. List of changes read here:

First post:

This is now stable version DebianDog started as Light-Wheezy+Porteus-Wheezy.

DebianDog is very small Debian Wheezy Live CD shaped to look like Puppy and act like Puppy. Debian structure and Debian behaviour are untouched and Debian documentation is 100% valid for DebianDog. You have access to all debian repositories using apt-get or synaptic.

To test DebianDog for first time you need to burn it on CD and boot from it, or use DebianDog-installer (included in the iso and working from most linux systems) to make frugal install to HDD or USB, or to extract /live folder on top of a partition or USB and edit grub menu.lst.

DebianDog is set to autologin as root. If you like to use it as multiuser system it is recommended to start XDM login manager (available only in Jwm version). Just type in terminal xdm-start and reboot. xdm-stop will reverse back autologin as root.

Login details:
root with password root
puppy with password puppy

Two versions are available for download:
1. DebianDog-Wheezy-jwm_icewm.iso -119 Mb
Default WM - JWM with option to switch to IceWM.
Default File Manager - XFE with option to use Rox.
Default Internet Browser - Dillo.

2. DebianDog-Wheezy-openbox_xfce.iso - 151 Mb (from Fred).
Default WM - OpenBox with XFCE.
Default File Manager - Thunar with option to use Rox or XFE.
Default Internet Browser - Firefox.

md5sum

DebianDog has kernel 3.2.0-4-486. If it works for your hardware you need nothing more. If it doesn't, please, read here how to boot easy with different kernel.
For modern multi-core machines it will be better to use (026-kernel-3.14-Pae.tar.gz - Debian kernel-3.14-0.bpo.1-686-Pae) or (022-kernel-686-pae.zip - Debian kernel-3.2.0-4-686-Pae) separate module from the link above.

We have 3 different initrd files included which gives 3 different boot and save file options. I will explain them proper in the next post.
Please, read also Examples-boot-codes for boot options.

After testing the boot methods and save file options and decide which one is best for you, just remove 2 initrd files to save 15 Mb system space.

Both versions have a lot in common as boot and save file options. The difference is in the WM and applications choice.

In post five on this page you will find information how to install packages in Debian with Synaptic (GUI) or apt-get (CLI).

DebianDog has lot of tools similar to Puppy. You can load puppy SFS modules and many of them will work out of the box. You can create easy separate sfs modules and remaster the system with all personal changes. You can convert pet packages to deb or sfs. I will give more information about the available tools in one of the next posts.

I like to give my Thanks to Smokey and KazzaMozz for hosting DebianDog project here, here, here,
to Debian team for keeping Debian such flexible system,
to this forum for the opportunity to work on a project different from puppy linux,
to our forum members working on DebianDog development: Fred (fredx181), Terry (sunburnt), William (mcewanw), Sergey (sklimkin),
and for the valuable advices to: jbv, sfs, catsezmoo, big_bass, emil, dancytron, anikin from our forum
and dzz from www.debianuserforums.org
And to Sickgut for his original idea that made possible DebianDog to exist.

Toni (aka 'saintless', DebianDog jwm_icewm maintainer)
