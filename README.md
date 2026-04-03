# Gecoos AC 2.2 for OpenWrt
### Note: Version 2.2 only supports Gecoos AP version ≥7.6. Lower firmware cannot receive configurations issued by the AC. It is recommended to update your AP's firmware to version 8.x.  
### Also, because version 2.2 of the AC adds new parameters, this repository is no longer compatible with AC firmwares below version 2.2.  
-------------------------------------------

### How to download the source code:

   ````
   # Download the source code
   git clone --depth=1 https://github.com/hiedgm/luci-app-gecoosac package/luci-app-gecoosac
   make menuconfig
   ````

### Configuration menu:

   ````
   make menuconfig
   # Go to LuCI -> Applications, select luci-app-gecoosac, save and exit.
   ````

### Compilation:

   ````
   # Compile the firmware
   make package/luci-app-gecoosac/compile V=s
   ````
