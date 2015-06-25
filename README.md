# linx7
Linx7 Tablet - Arch Linux

Use at own risk, no warrants whatsoever.

## Kernel
* Linux-mainline 4.1 Kernel with a minimal .config ([AUR](https://aur4.archlinux.org/packages/linux-mainline/))
* It is recommended to configure the kernel with `make menuconfig` (or other prefered method)

## Modules
* [WiFi](https://github.com/hadess/rtl8723bs)
* [Touchscreen](https://github.com/hadess/gt9xx)

## Patch Sources
* [rpmb-init-fix.patch](https://dev-nell.com/rpmb-emmc-errors-under-linux.html)
* [sdhci-pm.patch](https://github.com/AdamWill/baytrail-m/blob/master/kernel/MANIFEST)

## Bug Reports
* [byt-rt5640](https://bugzilla.kernel.org/show_bug.cgi?id=86581) (Audio)
