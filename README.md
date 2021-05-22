# gentoo-upgrade
Script for upgrading Gentoo Linux

# Installation
Add my overlay repository
Add repository with:
```
# eselect repository add alicela1ns-overlay git https://github.com/alicela1n/alicela1n-gentoo-overlay.git
# emaint sync -r alicela1ns-overlay
```

Unmask keywords! Right now I don't have a stable version of the script, so you'll need to either unmask ~(arch) or ** (live 9999).
You can unmask the ebuild like so:
```
# echo "app-portage/gentoo-update ~amd64" > /etc/portage/package.accept_keywords/gentoo-update
```

Install
```
# emerge --ask app-portage/gentoo-update
```

# Usage
```
# gentoo-update
```
