# Acer E5-575-OC
A Hackintosh EFI For Acer E5-575

# Screenshot
![IMG_20230724_093712_395](https://github.com/UnsuitableFollower/E5-575-OC/assets/88485719/e65d5d37-25eb-4c53-a9f3-6d33ec75f84a)

# Specification My Acer E5-575

| Category  | Component                            |
| --------- | ------------------------------------ |
| CPU       | Intel Core I3-6006u (Skylake)        |
| GPU       | Intel HD Graphics 520 (Spoof To HD 620) |
| SSD       | Teamgroup MP33 256GB M.2 NVMe SSD    |
| HDD       | Seagate 1TB HDD 5400rpm              |
| Memory    | 8GB DDR4 2133Mhz                     |
| Camera    | 720p Camera                          |
| WiFi & BT | Atheros 9377                         |
| Ethernet  | Realtek 8111

# What's Working

* Acceleration (QE/CI)
* Trackpad
* Audio
* Bluetooth
* Camera
* Power Management
* Sleep/Closing Lid
* Brightness

# Not Working

* Wifi `Need change Wifi Card Like Intel, Broadcomm,USB Dongle Wifi Or Workaround Using USB Terthering from your Phone, already includes HoRNDIS Kext`
* DRM

# Untested

* Type C Port
* HDMI
* Lot of stuff I don't bother to test.

# Notes
* If you want to reboot Mac OS to Windows, you are required to do a cold boot `(Shutdown And Power ON)` so that the Bluetooth on Windows is not broken
* Type C Still not remapped  `if you want type c, you can use the USBToolBox tool and Doing remapping USB`
* To use my EFI, you must generate [SMBios](https://github.com/corpnewt/GenSMBIOS) `For MacOS Ventura, Use SMBios MacBookPro14,1`

# Credit
    Thanks to Acidanthera for providing AppleALC, BrcmPatchRAM, HibernationFixup, Lilu, NVMeFix, OcBinaryData, OpenCorePkg,         RestrictEvents, VirtualSMC, VoodooInput, VoodooPS2, and WhateverGreen.
    Thanks to RehabMan and Sniki for providing BrightnessKey.
    Thanks to VoodooI2C for providing VoodooI2C.
    And thank you to Hackintosh Discord Server and some people I know from Telegram for helping me out creating this EFI!

#



