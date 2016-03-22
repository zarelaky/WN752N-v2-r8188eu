# r8188eu staging driver from kernel source tree

## build
. build.sh
## install
```
destdir=/lib/modules/$(uname -r)/kernel/drivers/staging/rtl8188eu
cp r8188eu.ko ${destdir}/r8188eu.ko
```
