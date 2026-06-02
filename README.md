# The-Sims-On-MacOS
Guide to install The Sims on MacOS. I tested it on my MacBook Air M3, but it shoudl work on all Apple silicon processors. 

Since this involves copyrighted software and the use of certain workarounds to get it running, I do not distribute or share any of the files, only the ones that are available online for free. The information below explains what you need. Please ensure you have all the required software and the corresponding activation codes before proceeding.

## Create The-Sims-CD
1. Extract The-Sims-CD.zip
1. Put your installation files of The Sims in a folder within the The-Sims-CD folder
2. Windows XP cannot be activated the normal way, so make sure you download an activator and put it in a folder within this folder as well
3. Open Disk Utility
4. Select file > New Image > Create from folder
5. Select the The-Sims-CD Folder
6. Select DVD Master as structure
7. After the ISO is made, open terminal and go to the folder with the The-Sims-CD.dvdr.cdr file
8. Give the following command: hdiutil makehybrid -iso -joliet -o The-Sims-CD.iso The-Sims-CD.dvdr.cdr

## Prepare the VM
1. Download the latest UTM version from their website
2. Open Windows XP.utm and use this as template
3. Open the settings of the VM
4. Under system give the VM 2 CPUs
5. Give the VM 4GB of memory
6. Select VGA as GPU and give it 256GB memory
7. Turn off Auto Resolution under Display

## Install Windows XP
1. Start the VM
3. Mount Windows XP Home with SP3
4. follow the installation steps and finish the installation
5. Shutdown Windows XP and open the settings
6. Remove the Network/LAN settings after the installation

## Settings and tools
1. Start the VM again
2. Install the Guest Tools from the CD menu on top of your VM and wait for it to complete the installation
3. Go to Display Properties and set the resolution to 1024x768 and check if 32bit color is selected
4. On the Display properties go to Settings and click advanced
5. Go to troubleshoot and set hardware acceleration to None
6. Right click on My Computer and select Properties, then Advanced and Performance settings.
7. Select Adjust for best performance
8. Mount The-Sims-CD.iso in Windows XP
9. Open the CD and open Windows Activation Tool
10. Click Get ID from System, and if the ID is generated, click Activate!
11. Install DirectX8a from the folder

## The Sims Complete Collection
1. Install The Sims Complete Collection with Start.exe
2. After installation, copy the No-CD Patch to the Program files/maxis/ folder
- Make sure to own a copy of the game and only use the No-CD Patch to get it work on your system
3. Place the mods in the downloads folder from Program files/maxis/ folder
4. Unzip the mods in the folder (cannot be done on the CD)
- You can use the mods by placing them in your house in the build mode, and let your sim interact with it. It makes playing this game much easier!
5. Start the game with the 1024x768 option
- The game won’t start or give you a black screen with the wrong resolution set in Windows
- If you want to play in full-screen, first go to Full screen, then check the resolution is still 1024x768 and then start the game

Start the game and enjoy!! 

# Support my work? 
If you like this guide and want to support my work, you can use the link below to buy me a coffee. Every bit of support is appreciated and helps me continue creating new content.

Buy me a Coffee: https://buymeacoffee.com/geejee
