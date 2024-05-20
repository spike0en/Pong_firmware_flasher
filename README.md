# Firmware Flasher for Nothing Phone (2)

A Firmware Flasher for Pong that automatically detects device info and flashes the target Firmware files. It ensures safe flashing by terminating if the correct device for the Firmware is not detected, reducing the risk of bricking devices.

# Features
 - Automatic detection of device type
 - The Firmware gets flashed to both A/B slots
 - Choice to Update modem.img or not (in 90% of the cases you choose yes here to update Modem)
   Only in some cases where you want to cross flash a different region Firmware it could be needed
   not to Update the modem.img as otherwise you might not have all 5G bands available for that region.

# Flashing procedure
- Download the firmware zip file corresponding to the target NothingOS (NOS) version from the download link above. (use Standard download on Mega not download as ZIP!)
- The firmware zip file can be flashed from a custom recovery via adb sideload or it can be directly flashed from the Internal Storage on the Phone (using TWRP/Orangefox).
- It doesnt matter on which NOS Version you are or if you are on a custom ROM or Stock NOS, you can just flash or sideload the Firmware file.
- It gets flashed to both slots so no need to flash it twice!
- Disable your Virusscanner on Windows before adb sideloading the file!
- The Firmware Flasher will not touch your data partition so it will not format or do anything to your Data.

# Supported Regions
- GLO
- IND
- EEA

# Download
- Firmware download: [Link](https://mega.nz/folder/2HQFUQAZ#C-clxkalqRQqS7i1KH-Mfg) (Use Standard download on Mega not download as ZIP, because then you get a ZIP file inside the ZIP file!)
- Alternatively users can fetch the firmware images from [here](https://github.com/spike0en/Pong_Archive) and repack them along with script in a supported flashable template

# Credits
- Nixsuki for the initial Version of the Oneplus Flashable Firmwares
- [WishmasterFlo](https://github.com/Wishmasterflo) for [Oneplus Firmware Flasher](https://github.com/Wishmasterflo/Firmware_flasher)
