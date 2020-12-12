# unipac - porting pacman to other distros

# Download
tgz package: https://github.com/glowiak/unipac/releases/download/tgz/unipac.tgz

# Installation
To install pacman and necessary libraries on your system just type as root: 'tar xzvf unipac.tgz --numeric-owner -C /'

# Deinstallation
Type as root:
  - rm /usr/bin/makepkg*
  - rm /usr/bin/pacman*
  - rm /etc/pacman.conf
  - rm -r /etc/pacman.d
  - rm -r /var/lib/pacman
