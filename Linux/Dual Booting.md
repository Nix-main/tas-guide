# Dual Booting
#### New OS, new me.
Dual Booting is a process where one installs a full additional operating system alongside their primary one in a partition of their disk file. A proper guide with images and additional information can be found [here](https://linuxblog.io/dual-boot-linux-windows-install-guide/). Simple steps are outlined below. 

Dual booting can be most easily done by installing the `ISO` or Disk Image File of whatever operating system you'd like. You should then plug in an external USB drive (does not need to be large, 8gb or more is recommended) and use a tool like [Rufus](https://rufus.ie/en/) (windows) or [Balena](https://etcher.balena.io/) (cross-platform) to "etch" the file onto the drive. This will make the drive "bootable", and by accessing your BIOS/UEFI settings or your computer's bootloader (if they are separate), you can boot from this drive.


Some Linux distributions, like Arch, will only open a very minimal installer, usually a command line. More user-friendly ones however, like [Ubuntu](https://ubuntu.com/download/desktop) (the recommended distribution for this) will make it very easy to install alongside your primary system.
