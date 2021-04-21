# gentoo-upgrade
Script for upgrading Gentoo Linux

# Installation
Add my overlay repository
Add repository with:
```
# eselect repository add alicela1ns-overlay git https://github.com/alicela1n/alicela1n-gentoo-overlay.git
# emaint sync -r alicela1ns-overlay
```
Install
```
emerge --ask app-portage/gentoo-update
```

# Usage
```
gentoo-update
```
