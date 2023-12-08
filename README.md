# BriarRose Gaming Virtual Machine
![1](https://github.com/Gamelover7825/BRVM/assets/44730743/99e5da16-9d12-4d04-9473-4d3393e98482)

## Installation/usage of latest Termux version
1. Install the provided versions of Termux, Termux-x11 and InputBridge
2. Put the BRVM.tar.gz file into the Download folder
3. Set up the following parameters in Termux-x11:

   *Display Resolution Mode = exact*
   
   *Display Resolution = 640x480, 800x600, 1024x768 or 1600x1200*
   
   *Show Additional Keyboard = disabled*
   
   *Fullscreen on Device Display = enabled*
   
4. Run the following commands in Termux:
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
6. Wait a few minutes while the virtual machine sets up. The desktop will appear when ready
7. To install games, copy them to the C: drive within Wine and run them from their executables
8. Every time you restart Termux, run the virtual machine using the 'brvm' command. If the desktop didn't start, type '1' in Termux and wait a few seconds



## Installation/usage of latest Standalone version
1. Copy the obb file to Android/obb/com.briarrose.vm
2. Install the APK, wait until the virtual machine is set up
3. Scroll down the upper panel and check the following boxes:

   *Render using new protocol*
   
   *Render using OpenGL ES 3.x*
   
   *Decompress textures (fixes graphical bugs)*
   
4. To install games, copy them to the C: drive within Wine and create shortcuts to their executables 
5. Tap 'Start Rendering' in the upper panel every time before you start a Direct3D game



## How to get games

You can find examples of pre-configured games in the following repository:

https://github.com/Gamelover7825/BRVM-PreconfiguredGames


## Video preview

https://youtu.be/KRvqqQESlO8


## Special thanks to

**alexvorxx:** VirGL and Turnip + Zink libraries

**Alpyne Dreams:** D8VK libraries

**doitsujin:** DXVK libraries

**DotNetBurst:** InputBridge

**Eltechs:** ExaGear

**Federico Dossena:** WineD3D Libraries

**Fredrick Fornwall:** Termux

**JeezDisReez:** glibc prefix for Termux

**mittorn:** VirGL overlay

**ptitSeb:** Box64

**WineHQ:** Wine
