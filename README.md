# Jike AC OpenWrt Plugin Version 2.2  
### Note: Version 2.2 only supports Jike AP firmware versions 7.6 and above. Lower version firmware cannot receive configurations issued by the AC. If possible, it's recommended to update your AP firmware to version 8.x.  
### Also, because version 2.2 of the soft AC adds new parameters, this repository is no longer compatible with AC programs below version 2.2.  
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

### Acknowledgments:
   ````
   Special thanks to lwb1978 for their hard work!
   ````
