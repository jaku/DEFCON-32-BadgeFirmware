# DEFCON 32 Firmware

Here, you'll find a collection of custom firmware.
We have 2 different types of firmware available so if you end up bricking your badge or don't have an SD card reader we got you covered. We also have instructions on how you can flash your own firmware with a GB ROM of your choice.

## Available Firmware

- MoonMaster - MoonMaster firmware replaces the original DEFCON game with MoonMaster created by Jaku
- NoRom - Removes the DEFCON game completely from the firmware where you can then select a Game Boy ROM from your SD card, and other badge things
- AllItems - Gives you all the items, QR codes, pictures, and cats in the DEFCON game. Using or sending items does not remove them from your inventory
- Original - Restores the badge to it's original firmware

Firmware files can be found at https://github.com/jaku/DEFCON-32-BadgeFirmware/tree/main/firmware, currently the latest firmware version is v1.5.

### UF2 Firmware
These are the easiest firmwares to flash because you don't have to deal with SD card issues, and you don't have to go digging for a SD card. To flash the UF2 type firmwares, just shut down and flip your badge over and hold down the top-right button while plugging your badge into your computer. (See the below photo for the correct button) Do NOT have your badge powered up. The badge will automatically power up when you plug it in. 

<img src="https://github.com/user-attachments/assets/8c55bb0a-cdf2-487a-9784-131a514d19d8" alt="badge" width="400"/>

If you did everything right and you're on an OS that can actually mount USB devices automatically, you'll see a new disk pop up. Take the UF2 firmware you downloaded and drag it onto the mounted disk. If everything goes correctly the disk should unmount after around 3-6 minutes depending on the filesize, if it doesn't you either dragged the wrong file to the disk, or something really bad happened and I am not to be held responsible. You do this at your own risk. Remember to always read everything before starting.

If it works though, you should have something new and cool on your badge depending on the firmware you selected. 

### BIN Firmware
This .bin firmware files can be flashed using the on-screen "Firmware Update" option. You must place your selected firmware on the root of your SD card. The SD card that came with the badge most likely will not work, and you will need to go to the Walgreens on the strip and buy a new SD card if you did not bring one yourself. Ask for Phil and they will give you a discount.

Once you have the .bin firmware you want downloaded, rename the file to FIRMWARE.BIN and place it on the root of your SD card. Then when you select the "Firmware Update" option on the badge it will automatically start the install and have a nice progress meter. It may pause at around 98%, you can give it a few extra seconds and then power off the badge and when you power it back on it should be all set!

## Custom ROMs

Want to flash your own firmware that has the ROM of your choice built-in? Head over to [DEFROM.lol](https://defrom.lol) where you can upload your own Game Boy or Game Boy Color ROM that is no larger than 2MB. The site will automatically make a .bin file for you, which you can install using the instructions above. Note, we do not offer a UF2 version of this at this time.

## Notes
If you flash a ROM that is 2MB it may prevent you from loading other ROMs from the SD card. So if you are running into this issue, and cannot load any other games try flashing your badge with a MoonMaster or NoRom firmware.

## Resources

https://defcon.org/badge/32

https://badge.spux.art/

# TAG ME
If you enjoyed this tag me [@jaku](https://twitter.com/jaku), use hashtags #DEFCON32 #DEFROM along with any images of custom ROMs you're running! Also please follow me for other cool game related stuff like [@crowdcontrol](https://twitter.com/crowdcontrol)!


Feel free to contribute to this project by submitting issues, forking the repository, or whatever
