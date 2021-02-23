# gentoo-upgrade
Script for upgrading Gentoo Linux

# Installation
**Currently broken ebuild, don't have a Gentoo install on hand to fix this at the moment**
Add my overlay repository
Add repository with:
```
# eselect repository add alicela1n-overlay git https://github.com/alicela1n/alicela1n-gentoo-overlay.git
# emaint sync -r alicela1n-overlay
```
Install
```
emerge --ask app-portage/gentoo-upgrade
```

# Usage
```
gentoo-update
```
