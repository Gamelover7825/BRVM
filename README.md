![1](https://github.com/yuraPIMENOV/BRVM/assets/44730743/99e5da16-9d12-4d04-9473-4d3393e98482)
# BriarRose Gaming Virtual Machine

## Installation of Termux versions
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
5. Restart Termux when a new line appears, then run the following command:
```
brvm
```
6. Open Termux-x11, you'll see the Wine desktop in a few seconds
7. Copy your own PC games to your mobile device's Download folder, they'll be seen in the D: drive
8. Copy the game to the C: drive or My Documents, and run the game's executable
9. Go to your game's controls settings, create a new profile in InputBridge, create some on-screen buttons for the keyboard and mouse controls, which the game is mapped to
10. Play your game on your mobile device
11. Every time you restart Termux, type 'brvm' to run this virtual machine



## Installation of Standalone versions
1. Copy the obb folder to Android/obb/*package_name*
2. Install the APK and wait until the cache is extracted
3. Copy your own PC games to your mobile device's Download folder, they'll be seen in your container's D: drive
4. Create a new container and select settings that suit your game
5. Run the container, copy the game to the C: drive or My Documents, and create a shortcut for your game's executable
6. Exit the container and run the game from the shortcuts list
7. If you use VirGL, check the following boxes:
   *Use new vtest protocol*
   *Use OpenGL ES 3.x instead of OpenGL*
   *DXTn decompress*
8. Tap 'Start Services' in VirGL every time you start a game



## Games that work well on VirGL
- Grand Theft Auto: San Andreas
- Grand Theft Auto: Vice City
- Hard Truck 2: King of the Road
- Need for Speed: Carbon
- Need for Speed: Most Wanted
- Need for Speed: Underground
- Shrek 2: The Game

## Games that work well on Turnip + Zink
- 18 Wheels of Steel: Across America
- 18 Wheels of Steel: Pedal to the Metal
- Grand Theft Auto: San Andreas
- Hard Truck 2 Beta
- Hard Truck 2: King of the Road
- Need for Speed: Carbon
- Need for Speed: Most Wanted
- Need for Speed: Underground
- Shrek 2: The Game
- Street Legal Racing: Redline
- WR Rally


## Special thanks to

alexvorxx - VirGL and Turnip + Zink libraries

Alpyne Dreams - D8VK libraries

doitsujin - DXVK libraries

DotNetBurst - InputBridge

Eltechs - ExaGear

Federico Dossena - WineD3D Libraries

Fredrick Fornwall - Termux

ptitSeb - Box64

WineHQ - Wine
