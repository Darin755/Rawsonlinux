#Rawson linux

This is Rawsonlinux 20 "TRAPPIST_3"

It is named after the TRAPPIST star system

it was created by Darin Rawson and Alex Rawson

To update Rawsonlinux config files from this Repo run Rawsonlinux-update as a non root user

Check out Rawson Linux website
https://sites.google.com/view/rawsonlinux/home

config.zip contains the home directory files

update.zip contains update related files

Rawsonlinuxscripts contains the scripts for Rawson Linux

when the script is run it will copy home directory files and folders
to the $HOME directory. It then copy the scripts from the Rawsonlinux directory to /usr/bin.
After that will configure lightdm.
Then it will install Jarvis. It then will clean up.

to install:

chmod +x install

./install
   -Do not run as root

Or use a disk image from our website
