# BriarRose Gaming Virtual Machine
![1](https://github.com/Gamelover7825/BRVM/assets/44730743/99e5da16-9d12-4d04-9473-4d3393e98482)

## System Requirements
### BRVM Termux versions
- 64-bit Android 10.0 and above
### BRVM Standalone versions / ExaGear
- 32 and 64-bit Android 5.0 and above
### Winlator
- 64-bit Android 9.0 and above
### Turnip + Zink graphic drivers for Direct3D games
- Adreno:  610 and above
- Mali: not supported
- PowerVR: not supported
- Tegra: not supported
### VirGL graphic drivers for Direct3D games
- Adreno: 405 and above
- Mali: T830 and above
- PowerVR: GE8300 and above
- Tegra: not supported

## Installation and usage
### Termux versions
1. Install the provided versions of Termux, Termux-x11 and InputBridge
2. Put the BRVM.tar.gz file into the Download folder
3. Run the following commands in Termux:
```
termux-setup-storage
```
```
tar -zxf /sdcard/Download/BRVM.tar.gz -C /data/data/com.termux/files --recursive-unlink --preserve-permissions
```
4. Restart Termux when a new line appears, then run the following command:
```
brvm
```
5. When the desktop is set up, copy your games to the C: drive within Wine and run them from their executables
6. Every time you restart Termux, run the virtual machine using the 'brvm' command

### Standalone versions
1. Copy the obb file to Android/obb/* package_name *
2. Install the APK, run it, then wait until the virtual machine is set up
3. Create a new container for your games
4. To install games, copy them to the C: drive within Wine and create shortcuts to their executables 
5. Tap 'Start Rendering' _('Start Services')_ in the Direct3D rendering settings panel _(VirGL overlay)_ every time before you start a Direct3D game with VirGL renderer



## Best configuration for external applications
### Termux-x11

***Display Resolution Mode** = exact*

***Display Resolution** = any (640x480 recommended)*

***Show Additional Keyboard** = disabled*

***Fullscreen on Device Display** = enabled*

### Direct3D Rendering Settings Panel / VirGL Overlay

***Render using new protocol** / **Use vtest protocol 2** = enabled*

***Render using OpenGL ES 3.x** / **Use GLES 3.x instead of OpenGL** = enabled*

***Render in multi-thread mode** / **Use multi-thread EGL access** = disabled*

***Decompress textures (fixes graphical bugs)** / **DXTn (S3TC) decompress** = enabled*

***Restart rendering service automatically** / **Auto restart services** = disabled*



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

**Eltechs:** ExaGear

**Federico Dossena:** WineD3D Libraries

**FoxRain:** Winlator AFEI

**Fredrick Fornwall:** Termux

**Herick75:** Box4Droid

**HUGO:** ExaGear 5in1

**Ilya114:** Box64Droid

**JeezDisReez:** glibc prefix for Termux

**mittorn:** VirGL overlay

**mr.frolof:** ExaGear MultiWine

**olegos2:** Termux-Box, Mobox

**Pipetto-crypto:** Androbox

**ptitSeb:** Box64

**Rob Clark:** Freedreno Turnip drivers

**WineHQ:** Wine
