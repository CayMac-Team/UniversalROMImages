# Universal ROMs
ROM Images for Quadra/LC &amp; Others

You must have & use one of our new Universal ROM SIMMs in either 8MB or 4MB as this ROM SIMM has the ability to sense what machine it is in and adapat to use the proper pinning for the machine. The Universal ROM will work in any of the original Macintosh IIsi base ROM compatible machines including the SE/30. When the LED on the SIMM is on, it is in the IIsi mode (in programmer and machine). When LED is off, it is in the LC/Quadra mode. It would be beneficial for you to have a ROMmate v1 or v2 programmer to change the image on your ROM SIMM. Most LC and Quadra machines have the location for a 64 pin ROM SIMM socket but the socket is not on the board. You will have to source and add this socket yourself or have someone else do it for you. When you purchase a ROM SIMM from CayMac Vintage, you have an option to add a 64 pin simm socket with metal clips.

[Universal 8MB ROM SIMMs can be found here](https://ko-fi.com/s/2bee7a6f82)


[ROMmate v2 Programmer can be found here](https://ko-fi.com/s/d6e7e4494d)

### LIMITATION
Boot from ROM is only working with ZuluSCSI or blueSCSI attached. Will NOT work with others or spinner drives. This is a known issue at this time with all intentions to have a fix for it soon.

### **WARNING & Use At Own Risk Statement**
ROM modifactions is a Work In Progress and not all is 100% operational. Constant code changes are being made and new images released to provide additional features and abilities to the ROM images. Use at your own RISK and CayMac Vintage nor any of its team members are liable. There is NO warranty provided. This is a hobby for us all as such. DO NOT use the earlier standard ROM in a Quadra or LC machine as the pinout is differend and it WILL damage the ROM SIMM.

# Current ROM Images
### Directory LC475_LC575_Q650

**Notes**
  - Works on 605/610/650/800/475/575
  - Boot image has 040/065 enabler
  - Boot imase is OS7.1
  - djMEMC Large RAM support for 610/650/800
    - 610 - 250MB
    - 650/800 - 520MB 
  - RAM check disabled
  - No checksum check
  - ROMs with a boot SYSTEM - hold R to load from ROM or hold A & R to load from ROM into a RAM drive (16mb or more RAM required). Hold key(s) as soon as the arrow appears and before the happy Mac boot icon. After icon appears, you can release the key(s).

  **File(s)**
  - **LC475_LC575_Q650_4MB_WITH_SYSTEM.ROM** - ROM with Boot Image for 4MB SIMM
  - **LC475_LC575_Q650_8MB_WITH_SYSTEM.ROM** - ROM with Boot Image for 8MB SIMM
  - **LC475_LC575_Q650.ROM** - Base ROM only no Boot Image 1MB file size can put on any SIMM alone
  - **3MB_SYSTEM_BOOT_ENB_040_065.DSK** - Boot Image 3MB file size add to Base ROM to make a 4MB ROM SIMM. Can also boot on blueSCSI or emulator

### Directory Q700_Q900_Q950

**Notes**
  - No checksum check
  - Boot image is OS7.1
  - RAM check disabled
  - ROMs with a boot SYSTEM - hold R to load from ROM or hold A & R to load from ROM into a RAM drive (16mb or more RAM required). Hold key(s) as soon as the arrow appears and before the happy Mac boot icon. After icon appears, you can release the key(s).

  **File(s)**
  - Quadra 950_no_mem_no_checksum_ROM_drive_4MB_System.ROM - Base ROM with 3MB boot image for 4MB rom simm
  - Quadra 950_no_mem_no_checksum_ROM_drive_8MB_System.ROM - Base ROM with 7MB boot image for 8MB rom simm
  - Quadra 950_no_mem_no_checksum_ROM_driver_BASE.ROM - Base ROM with no boot image

