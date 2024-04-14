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

### Termux-x11 best settings

***Display Resolution Mode** = exact*

***Display Resolution** = any resolution supported by your BRVM version*

***Show Additional Keyboard** = disabled*

***Fullscreen on Device Display** = enabled* 


## How to get games

In the following repository, you can find some pre-configured games:

https://github.com/Gamelover7825/BRVM-PreconfiguredGames


## Video preview

https://youtu.be/KRvqqQESlO8


## Special thanks to

**alexvorxx:** VirGL and Turnip + Zink libraries

**Alpyne Dreams:** D8VK libraries

**brunodev85:** Winlator

**doitsujin:** DXVK libraries

**DotNetBurst:** InputBridge

**DreamWorks Animation LLC:** the 2 women on the project logo

**Federico Dossena:** WineD3D Libraries

**FoxRain:** Winlator AFEI

**Fredrick Fornwall:** Termux

**Herick75:** Box4Droid

**Ilya114:** Box64Droid

**JeezDisReez:** glibc prefix for Termux

**olegos2:** Termux-Box, Mobox

**Pipetto-crypto:** Androbox

**ptitSeb:** Box64

**Rob Clark:** Freedreno Turnip drivers

**WineHQ:** Wine
