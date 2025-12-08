# Flintux OS

**Flintux OS is a linux distribution based on the monolithic linux kernel that aims to be light on resources and minimalist.**

Flintux OS is built with buildroot. This means that it can be configured using the 'make menuconfig' command in the source code directory, then it can be built into a .img file using the 'make' command to be used in an external drive.

### Issues that should be noted before building
- 'make savedefconfig' command will give an error if the name of the folder of the build environment is changed, this can be fixed by changing the defconfig location at 'BR2_DEFCONFIG' option in the .config file.

## Init System
Flintux OS uses BusyBox as its main init system to be simple to understand and fast.

## Window Manager
Flintux OS uses 'twm' as its window manager due to it being customizable and lightweight. Since it is a pretty old window manager, finding tutorials for doing certain things with twm shouldn't be too difficult.

## Package Manager
At the moment, Flintux OS does **NOT** support any package managers, this is definetly a dealbreaker for some but until package repositories are added it will not exist.
