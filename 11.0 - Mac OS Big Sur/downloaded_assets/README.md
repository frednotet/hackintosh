# Guides

[https://dortania.github.io/OpenCore-Install-Guide/](https://dortania.github.io/OpenCore-Install-Guide/)

# Hardware

**Motherboard:**
MSI Z170A XPOWER GAMING TITANIUM EDITION (MS-7968)

**CPU:**
Intel(R) Core(TM) i5-6600K CPU 3.50 GHz

**Graphic Card:**
XFX Radeon RX 5700 XT DD 8GB DDR6 3xDP HDMI Graphics Card

**Ethernet:**
Intel(R) Ethernet Connection (2) I219-V

**Wifi/Bluetooth:**
Fenvi FV-T919

**Hard Drive:**
SAMSUNG 860 EVO - 1TB (V-NAND SSD)

# Preparation

- Download from App Store.

- Format USB Key with `Disk Utility`.

- Run following command:

```
$ sudo /Applications/Install\ macOS\ Big\ Sur.app/Contents/Resources/createinstallmedia --volume /Volumes/USB
Password:
Ready to start.
To continue we need to erase the volume at /Volumes/USB.
If you wish to continue type (Y) then press return: Y
Erasing disk: 0%... 10%... 20%... 30%... 100%
Copying to disk: 0%... 10%... 20%... 30%... 40%... 50%... 60%... 70%... 80%... 90%... 100%
Making disk bootable...
Install media now available at "/Volumes/Install macOS Big Sur"
```

- Prepare EFI Folder

- handle `config.plist`.

[https://dortania.github.io/OpenCore-Install-Guide/config.plist/skylake.html#starting-point](https://dortania.github.io/OpenCore-Install-Guide/config.plist/skylake.html#starting-point)

