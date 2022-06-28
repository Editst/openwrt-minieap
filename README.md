# minieap for OpenWrt

## Build

First download [OpenWrt SDK](https://downloads.openwrt.org/) for your device.

```sh
cd /path/to/your/sdk
git clone https://github.com/Editst/openwrt-minieap.git package/minieap
make menuconfig # choose `minieap` in section `Network`
make package/minieap/compile V=s
```

## SYSU Config

`minieap -u netid -p password -n eth0 -e 20 -d 0 -b 3 -w`
