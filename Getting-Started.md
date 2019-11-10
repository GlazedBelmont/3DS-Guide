### Getting Started
This will get you the steps of fastboot3DS and Luma3DS, but first make sure to update to the latest version (currently 11.12.0-44)

### Seedminer
Seedminer is an unpatchable exlpoit that allows you to bruteforce your movable.sed and sign custom saves, we will use this to sign a hacked save allowing us to boot custom code (in our case, fb3dstool)

### Prerequisites
 - internet connection on 3DS
 - browser access on PC
 - SD access on PC (or phone)
 
 ### Instructions
 1. navigate to the Nintendo 3DS folder on your SD card
 2. Copy the 32 character long name of the folder you see inside Nintendo 3DS
    - the 32 character long name is called id0, and will be referred to that for the rest of the guide
    - if you have two or more of these folders, then rename the Nintendo 3DS folder to BACKUP_Nintendo 3DS
    - put back in 3DS, and boot, then turn off and put SD back in PC
    - Copy the 32 character long name of the folder you see in Nintendo 3DS folder
    - Delete the Nintendo 3DS folder and rename backup to Nintendo 3DS
 3. Save the id0, and your friend code for later
 4. Go [here](https://bruteforcemovable.com/) and paste the id0 and friend code, then follow it's steps to get your movable.sed
 5. Go [here](https://bb3.bruteforcemovable.com/) and input your movable.sed, press Start, and download the .zip then extract the F00D43D5.bin from it
 6. Paste the F00D43D5.bin in SD:/Nintendo 3DS/id0/id1/Nintendo DSiWare/
 7. On 3DS, go to Settings -> Data Management -> DSiWare -> SD
 8. Power off your device, and save 42383841.bin from the SD root to PC for later
 9. Download [this](https://github.com/Multimegamander/3DS-Guide/CFWPack.zip) and extract the files/folder to the root of your SD
 10. Go [here](https://fredtool.bruteforcemovable.com/) and follow it's instructions, using 42383841.bin as dsiware.bin
 11. Place the output file in SD:/Nintendo 3DS/id0/id1/Nintendo DSiWare/ replacing any .bin files in the dir.
 12. Turn on 3DS, go to Settings -> Data Management -> DSiWare -> SD and copy Haxxxxxxxxx! to System Memory
 13. Return to Settings, and go to Internet Settings -> Nintendo DS Connections, then press OK, you should be in flipnote studio.
 14. Select the left option every time until welcome screen is over, select the large left box, then the box with an SD card on it, select the face and then the bottom right icon.
 15. Press X or UP depending on which it says, then press the film reel icon, then scroll until the 3rd box is selected, and tap the 4th box with the letter A in it.
 16. Use the app to install fastboot3DS
 17. Read the [fastboot3DS readme](https://github.com/derrekr/fastboot3DS/blob/master/README.md) to understand how to use it
 18. After setting up fastboot3DS, hold Select on boot to choose what you want in Luma3DS settings.
