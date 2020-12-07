# gentoo-upgrade
Script for upgrading Gentoo Linux

# Installation
Add my overlay repository
Add repository with:
```
# eselect repository add lyras-overlay git https://github.com/lyra64/lyra-gentoo-overlay.git
# emaint sync -r lyras-overlay
```
Install
```
emerge --ask app-portage/gentoo-upgrade
```

# Usage
```
gentoo-update
```
