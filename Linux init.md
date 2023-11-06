## Linux driver for rtl8188ftv USB Dongle:

Do as what this page says; it worked on Mint, Ubuntu and MXLinux: 

https://github.com/kelebek333/rtl8188fu

## VPN:

To use v2ray configs download linux-64 version of Xray from here:

https://github.com/XTLS/Xray-core/releases/latest

In the v2ray android app, choose 'Export full configuartion to clipboard' and then somehow transfer the resutlt to your PC and save it in the Xray app folder with 'conf.json' name.
Run the following command to run xray with conf.json:

./xray run -c conf.json
