![1](https://github.com/yuraPIMENOV/BRVM/assets/44730743/99e5da16-9d12-4d04-9473-4d3393e98482)
# BriarRose Gaming Virtual Machine
A Linux+Box64+Wine-based Termux container that runs PC (Windows) games on Qualcomm Snapdragon-powered Android smartphones and tablets

Installation:
1. Install the provided versions of Termux, Termux-x11 and InputBridge
2. Put the BRVM.tar.gz file into the Download folder
3. Set up the following parameters in Termux-x11:

   *Display Resolution Mode = exact*
   
   *Display Resolution = 640x480*
   
   *Show Additional Keyboard = disabled*
   
   *Fullscreen on Device Display = enabled*
   
5. Run the following commands in Termux:
```
termux-setup-storage
```
```
tar -zxf /sdcard/Download/BRVM.tar.gz -C /data/data/com.termux/files --recursive-unlink --preserve-permissions
```
5. Restart Termux, run the following command:
```
brvm
```
6. Open Termux-x11, you'll see the Wine desktop in a few seconds
7. Copy your own PC games to your mobile device's Download folder, they'll be seen in the D: drive
8. Copy the game to the C: drive or My Documents, and run the game's executable
9. Go to your game's controls settings, create a new profile in InputBridge, create some on-screen buttons for the keyboard and mouse controls, which the game is mapped to
10. Play your game on your mobile device



# Special thanks to:

ptitSeb - Box64

WineHQ - Wine

Fredrick Fornwall - Termux

DotNetBurst - InputBridge
