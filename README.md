# t490-hackintosh

## Screenshot:
![Capture d’écran 2022-10-31 à 19 21 01](https://user-images.githubusercontent.com/86233/199081421-07b3ed98-4b7d-444c-8da8-aaf7bccb7a10.png)


## Updates:
31/10/2022: Working with Ventura 13.0 !

## Infos:
This repo contains files needed to "Hackintosh" your Lenovo T490, model number 20NL-000LFR (Core i7, 16GB RAM)
You have to change your drive if your model is a Samsung P981. This model encounter some errors when it used with macOS.
More info here: https://dortania.github.io/Anti-Hackintosh-Buyers-Guide/Storage.html

It contains:
- OpenCore version 0.8.5
- All the kexts and patch needed to run MacOS Ventura 13.0 on your Lenovo T490
- config.plist (but you need to configure your ROM, MLB, etc.. to suit your needs)

## Working:
- Sound
- Wifi
- HDMI output
- Ethernet port
- Trackpad (with gesture)
- USB ports
- Jack Sound Plug
- Sleep (close and open lid)
- Backlight

## Not tested:
- USB-C / Thunderbold port

## Not working
- Micro SD Card Slot

## How To:
- Clone the content of this repo into your computer
- Copy the BOOT and OC folder into your EFI partition
- Modifiy the config.plist to suit your needs (ROM, MLB, etc...)
- Enjoy :)

## Thanks
yusifsalam with his repo for T490 and Big Sure:
https://github.com/yusifsalam/t490-macos

