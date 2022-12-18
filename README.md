[![Build OpenWrt](https://github.com/minax007/XIAOMI_MI_AC2100_R2100_OpenWrt/actions/workflows/build-snapshot.yml/badge.svg)](https://github.com/minax007/XIAOMI_MI_AC2100_R2100_OpenWrt/actions/workflows/build-snapshot.yml)
[![release](https://img.shields.io/github/v/release/minax007/XIAOMI_MI_AC2100_R2100_OpenWrt.svg)](https://github.com/minax007/XIAOMI_MI_AC2100_R2100_OpenWrt/releases)


# OpenWrt snapshot for Xiaomi Mi AC2100 (R2100)

This GitHub action is to build fresh images of latest OpenWrt snapshot using imagebuilder.

![grafik](https://user-images.githubusercontent.com/67478561/116359547-33a6ca80-a7ff-11eb-8158-67341a4f01b5.png)

Following packages are already installed, so that you do not need to install them via the command line afterwards: 

Added features | Package names
------------ | -------------
**LuCI GUI** | luci
**LuCI Material Theme** | luci-theme-material 
**LuCI Bandwidth Monitor** | luci-app-nlbwmon
**LuCI SQM (QoS)** | luci-app-sqm
__________________________________________________________________
**Official OpenWrt snapshot build without LuCI:**

https://firmware-selector.openwrt.org/?version=SNAPSHOT&target=ramips%2Fmt7621&id=xiaomi_mi-router-ac2100
__________________________________________________________________
**Official OpenWrt snapshot download directory for MT7621 routers, which includes the imagebuilder used in this action script:**

https://downloads.openwrt.org/snapshots/targets/ramips/mt7621/
