# HP EliteBook 840 G6 Hackintosh

A HP EliteBook 840 G6 Hackintosh running macOS Big Sur 11.6.4, built using OpenCore 0.7.8


## Laptop Specs

* macOS Big Sur 11.6.4
* Intel i5-8265U @ 1.6 Ghz (4 cores, 8 threads)
* Samsung M471A2K43CB1-CTD 32GB DDR4-RAM SDRAM SO-DIMM @ 2400 Mhz
* Intel UHD Graphics 620 1536 Mb
* Defualt M.2 NVME Samsung MZVLB256HAHQ Drive is incompatible with macOS (The installer will hang/freeze after 5 minutes so swap this for any drive not made by Samsung. I'm using a cheap M.2 Sata SSD from Liteon)
* 13" Screen

## What works

* **WIFI & Bluetooth !** Using default Intel AX200 Wi-Fi
* Speakers
* Headphones output
* Trackpad with gestures
* USB 3 + USB C Ports (Haven't tested Thunderbolt as I don't have any adpaters :( )
* LAN/Ethernet
* Fn keys to change volume or brightness
* Battery percentage/status
* Sleep/Wake-up
* FileVault
* Joystick (Nipple mouse)

## Doesn't work

* **Webcam :** Depends of the Webcam vendor & model. Can work or not.
* **Smart Card Reader :** Not tested, I disabled it in the BIOS.

