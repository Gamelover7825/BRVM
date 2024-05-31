# BriarRose Gaming Virtual Machine
![1](https://github.com/Gamelover7825/BRVM/assets/44730743/99e5da16-9d12-4d04-9473-4d3393e98482)

**Discord server:** https://discord.gg/PNUGHgDUb6

## Requirements
**OS:** 64-bit Android 10.0+

**GPU:** Adreno 610+ _(Mali and PowerVR not supported)_

**RAM:** 6+ GB

## Installation and usage
1. Install the provided versions of Termux, Termux-x11 and InputBridge
2. Put the BRVM.tar.gz file into the Download folder
3. Run the following commands in Termux:
```
termux-setup-storage
```
```
tar -zxf /sdcard/Download/BRVM.tar.gz -C /data/data/com.termux/files --recursive-unlink --preserve-permissions
```
4. Restart Termux when a new line appears, then run the virtual machine using the `brvm` command
5. When the desktop is set up, copy your games to the C: drive within Wine and run them from their executables
6. Every time you restart Termux, run the virtual machine using the `brvm` command

## Recommended Termux-x11 settings

***Display Resolution Mode** = exact*

***Display Resolution** = 800x600*

***Show Additional Keyboard** = disabled*

***Fullscreen on Device Display** = enabled* 


## How to get games

In the following repository, you can find some pre-configured games:

https://github.com/Gamelover7825/BRVM-PreconfiguredGames


## How to run games directly from the homescreen


1. Make sure that a supported BRVM version is installed and completely set up, Termux allows _notifications_ and _drawing over other apps_
2. Install _Activity Launcher_ and _Termux Widget_
3. Create a folder _.shortcuts_ in _Z:\home_ inside BRVM if not exist, sometimes that folder is linked to _My Documents_, place there the shortcut script file for your game and BRVM version
4. Using the activity launcher, run the _Termux Shortcut_ activity of the _Termux Widget_ app, and tap on the shortcut you made to add it to the homescreen
5. The game may be run minimized, tap _Termux_ in the notification panel to open it. If you have done everything correctly, your game will be run instead of the file manager
6. If the game does not run directly from the shortcut, enable _Force landscape orientation_ in Termux-x11
7. Some games may require a specific action to be run from shortcut



## Development builds

In the following repository, you can find some development builds of the project and experimental pre-configured games:

https://github.com/Gamelover7825/BRVM-Development


## Video preview

https://youtu.be/KRvqqQESlO8


## Special thanks to

**alexvorxx:** Turnip + Zink libraries for Direct3D support in the project

**Alpyne Dreams:** D8VK libraries, used by Direct3D 8 games

**doitsujin:** DXVK libraries, used by Direct3D 9-12 games

**DotNetBurst:** InputBridge controls overlay

**DreamWorks Animation LLC:** the 2 women on the project logo

**Fredrick Fornwall:** Termux

**JeezDisReez:** glibc prefix for Termux

**olegos2:** Mobox, the emulator which the project is built on the top of

**ptitSeb:** Box64 and Box86 compatibility layers

**Rob Clark:** Freedreno Turnip drivers for Qualcomm Snapdragon chips

**WineHQ:** Wine compatibility layer
