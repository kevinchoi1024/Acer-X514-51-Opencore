# Acer-X514-51-Opencore
Acer X514-51 Hackintosh EFI with Opencore 0.8.5

Open Core 0.8.5 Ventura Beta 3 full working Hackintosh with Acer TMX514-51 with opencore 0.8.5


This repository contains EFI partition files for Acer Acer TMX514-51 Hackintoshed laptop.

YOU MUST CREATE YOUR OWN SYSUUID, MLB, SERIAL BEFORE BOOTING YOUR LAPTOP WITH THIS EFI sysUUID, MLD, Serial must be created for your own.

Acer X514-51 Specs: intel i5-8265u (UHD620), intel WiFi & Bluetooth

What works: Everything except that doesn't work

What doesn't work:
Fingerprint Sensor
Internal microphone
Combojack conversion from headphone -> headset. (Microphone input does not work)

Note: 
1. AirportItlwm.kext currently in EFI/OC/Kexts is unstable. It is recommended to update to stable releases.
2. DSDT file is in place for functionality of internal trackpad. Any ideas for using trackpad without this DSDT file will be appreciated.

Any changes are appreciated. Enjoy.
