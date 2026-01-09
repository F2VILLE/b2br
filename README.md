*This project has been created as part of the 42 curriculum by fdeville*

## Description
This is a Debian 13 (LTS as of now) VM with the goal of learning how to setup a Linux server environment and the basics of security.

#### Debian vs Rocky
Two different Linux distros. 
Debian is one of the most used distro, and has a ton of documentation / references and a big community. 
Rocky uses sources from RedHat and is based on RHEL (Red Hat Enterprise Linux), meaning it is pretty secure and stable for enterprises.

#### AppArmor vs SELinux
Those are Mandatory Access Control systems. 
Those are shipped respectively with Debian and Rocky.
AppArmor is more user-friendly than SELinux, but with the cost of being less customizable (And by default is more permissive).

#### UFW vs firewalld
UFW and firewalld are both tools that helps to filter network interactions.
UFW seems more simple than firewalld, so which one to use really depends on the use case. 
Firewalld needs a bit more configuration, whereas UFW is usually used in command line with an easy syntax (eg. `ufw default deny`, `ufw allow 22/tcp`)

#### VirtualBox vs UTM
Those are virtualization tools made to run virtual machines.
UTM is essentially aiming macOS and the Apple ecosystem with support of the Apple Silicon.
Oracle VirtualBox is cross platform.
So here the use case depends if you aim to run an ARM or x86-64 system.

## Instructions
The `signature.txt` file is the sha1sum of the VDI (Virtual Disk Image) file of the VM. \
LVM encryption password : `42belgium` \
User (fdeville) and root password : `42Belgiums19`

## Resources

### AI

When searching things on Google the AI summary is pretty helpful to have access to informations quickly, but it can sometimes lack of accuracy, therefore I usually try to check some websites in addition.

### Links and websites
Especially for the setup of the system, the Debian wiki was quite useful. \
Plenty of ressources from GeeksForGeeks and other similar websites. \
Reddit and StackOverflow / StackExchange also are pretty useful to get answers when encountering problems or searching for specific cases.

Some links : \
https://wiki.debian.org \
https://crontab.guru/every-5-minutes \
https://www.geeksforgeeks.org/linux-unix/useful-sudoers-configurations-for-setting-sudo-in-linux/
