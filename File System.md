# File System

## what is different types of directory under root (/) directories 

 ```
   /boot : Bootable linux Kernel and bootloader config files
   
   /dev : Files representing devices. tty=terminal, fd=floppydisk, (sd or hd) = harddisks, ram=RAM, cd=CD-ROM 
   /media : Unlike /dev, /media is usually where removable media (USB sticks, external hard drives etc.) are mounted.
   /mnt:  : A place to mount external devices. This can still be used but has been superseded by /media
   
   /home : Where the home directories for regular users are stored. For example, mine is at /home/peekay
   /root: The home folder for the root user aka the superuser (similar to the administrator on Windows)
   
   /bin : Stores Common Linux user command binaries. e.g date, cat, cal commands are in here.
   /sbin: Contains administrative commands (binaries) for the root (super) user.
   /lib: Contains shared libraries needed by applications in /bin and /sbin to boot the system.
   
   /tmp: Contains temporary files used by running applications
   /etc: Administrative Configuration files. The format for many of these configuration can be found in section 5 of the Linux Manual.
   /misc : A directory used to sometimes automount filesystems on request.
   /opt: Directory Structure used to store additional (i.e optional) software
   /proc: Information about System Resources
   /usr: Contains files pertaining to users that in theory don’t change after installation.
   /var: Contains directories of variable data that could be used by various applications. System log files are usually found here.
```
