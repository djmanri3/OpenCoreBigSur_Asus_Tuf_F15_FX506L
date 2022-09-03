# OpenCoreBigSur_Asus_Tuf_F15_FX506L

# Spects:
CPU	Intel® Core™ i7-10750H 6 cores

iGPU	Intel® UHD Graphics 630

RAM	16GB DDR4

Storage 1TB SSD M2

Audio	ALC(256)

Wifi + Bluetooth

# What do we need?

- USB with a capacity greater than 16gb
- HDD / SSD greater than 35.5gb
- OpenCore Utilities: https://github.com/acidanthera/OpenCorePkg
- Patience and time :)

# Steps:

- Format your USB to FAT32 and copy the files from this repo (EFI folder)

- Go to OpenCore-x.x.x.x-RELEASE \ Utilities \ macrecovery open cmd and paste the following command: 
./macrecovery.py -b Mac-E43C1C25D4880AD6 -m 00000000000000000 -os latest download

- Create a folder in the root of our USB memory called com.apple.recovery.boot and we will copy the following downloaded files
  * BaseSystem.dmg
  * BaseSystem.chunklist

- Finally we will boot from our USB drive, and we will go to the disk utility and format our hdd / ssd to APFS

- When the installation is finished do not panic if it takes a long time to finish or there are reboots, it takes its own time

# Big Sur
### BUGS:
- AirDrop
- HDMI and type c screen (This problem comes from the nvidia graphics :( ) (Solved Display Link USB)
- Audio through the minijack (works but can't be heard correctly) (Solved audio bluetoth)

### WORKING:
- WiFi
- Bluetoth
- Power botton
- Keyboard
- Type c
- Touchpad
- Slot of micro SD
- Speakers
- Ethernet
- Sensors
- Control of batery

# Monterey
### BUGS:
- AirDrop
- HDMI and type c screen (This problem comes from the nvidia graphics :( )
- Audio through the minijack (works but can't be heard correctly) (Solved audio bluetoth)
- USBS
- Controler of disks (Only view one disk)
- Trackpad

### WORKING:
- WiFi
- Bluetoth
- Power botton
- Keyboard
- Type c
- Slot of micro SD
- Speakers
- Ethernet
- Sensors
- Control of batery

# I want to thank the guys at OpenCore and the different groups that have helped me carry out the work for the beautiful work :)

Telegram:
- https://t.me/hackintosh_spain
- https://t.me/c/1071950348/180432

Guide used:
- https://dortania.github.io/OpenCore-Install-Guide/

Youtube channel where it is explained step by step
- https://www.youtube.com/watch?v=-GLyfS0eI5g

