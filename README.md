# linx7
Linx7 Tablet - Arch Linux

Use at own risk, no warranties whatsoever.

## Kernel
* Linux-mainline 4.2RC5 Kernel with a minimal .config ([AUR](https://aur.archlinux.org/packages/linux-mainline/))
* It is recommended to configure the kernel with `make menuconfig` (or other prefered method)

## Modules
* [WiFi](https://github.com/hadess/rtl8723bs)
* [Touchscreen](https://github.com/hadess/gt9xx) *optional

## Patch Sources
* [rpmb-init-fix.patch](https://dev-nell.com/rpmb-emmc-errors-under-linux.html)
* [sdhci-pm.patch](http://thread.gmane.org/gmane.linux.kernel.mmc/25081/focus=25087)

## Bug Reports
* [byt-rt5640](https://bugzilla.kernel.org/show_bug.cgi?id=86581) (Audio)
