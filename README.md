# BittBoyV1
Various fixes and tinkering for CFW for the New BittBoy version 1.

The image(s) available here are just updates/tweaks to the original SD card image provided by steward via his GitHub.  You can visit his GitHub at https://github.com/steward-fu/miyoo_rel.  

# This image requires a minimum of a 8GB micro SD card.  If using a larger micro SD card, you can expand the main Fat32 partition using a Windows based Partition tool like MiniTool Partition Wizard - Free Edition (https://www.partitionwizard.com/download.html).  I do not suggest using a linux based tool such as GParted as it seems to cause issues with Fat32 partitions being readable on Windows machines.

  ## The tweaks in my image(s) are as follows:
-  Default kernel is the one that supports the hardware mod based ghost key fix.  
   -  For New BittBoy V1 without this mod, you can download the default kernel from Steward's Github via https://github.com/steward-fu/miyoo_rel/blob/master/kernel/kernel_20190218.zip, unzip and place the kernel file (r61520fb.ko) in main/kernel folder replacing the existing kernel there.
-  Added gmenu2x with update to R button to allow quick press to suspend, long press to bring up power menu. (Not my fix, just implemented in image.)
-  TA and TB button scroll through gmenu2x sections (Not my fix, just implemented in image.)
-  Added gpsp emulator update with button remapping (Thanks Sauce!)
-  Added gambatte as an alternative GB/GBC emulator (Thanks Hi-Ban!)
-  Added Wolfenstein 3D as another available game (Thanks Steward!)
-  Added Batman TC mod for Doom2 as an additional game.  Using Chocolate Doom executable.
-  Check and fix Main fat32 partition corruption on boot to improve stability.
-  Additional changes will be noted on new image notices in the releases section

#  Instructions
-  Windows users:
   -  Download the image.  
      -  You can get the split files from the releases section located here or download the full 7zip file from https://mega.nz/#F!TYBREKgI!TDZnZrUd2PWKgwkq3_RJ5g
   -  Unzip the image (I suggest using the free 7zip tool from https://www.7-zip.org/download.html)
   -  Use a program such as Win32DiskImager (https://sourceforge.net/projects/win32diskimager/) or Etcher (https://www.balena.io/etcher/) to flash to a 8GB micro SD card or larger.
   -  Load some roms into the roms folder (I suggest them putting them in seperate folders based on platform for organization)
   -  Insert into V1 New BittBoy and enjoy!   

-  Linux users (Instructions are based on Ubuntu 16.04 as this is the Linux OS I use):
   -  Download the image.  
      -  You can get the split files from the releases section located here or download the full 7zip file from https://mega.nz/#F!TYBREKgI!TDZnZrUd2PWKgwkq3_RJ5g
   -  Unzip the image (I suggest using the free 7zip tool.  From terminal, you can install this by doing sudo apt-get install p7zip-full p7zip-rar)   
   -  For those with Ubuntu based systems, you can use the Disks app to image to a 8GB micro SD card or larger.
   -  Load some roms into the roms folder (I suggest them putting them in seperate folders based on platform for organization)
   -  Insert into V1 New BittBoy and enjoy!   
