# BriarRose Gaming Virtual Machine
![1](https://github.com/Gamelover7825/BRVM/assets/44730743/99e5da16-9d12-4d04-9473-4d3393e98482)

## System Requirements
### Emulators
- ExaGear: 32 and 64-bit Android 5.0 and above
- Winlator: 64-bit Android 9.0 and above
- Termux _(Box64Droid, Termux-Box, Androbox, Mobox)_: 64-bit Android 10.0 and above
### Turnip + Zink graphic drivers for Direct3D games
- Adreno: 610 and above
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

### Termux-x11 best settings

***Display Resolution Mode** = exact*

***Display Resolution** = any resolution supported by your BRVM version*

***Show Additional Keyboard** = disabled*

***Fullscreen on Device Display** = enabled*

### Standalone versions
1. Name the OBB file (system image) as _main.30.com.briarrose.vm.obb_, copy it to _sdcard/Android/obb/com.briarrose.vm_
2. If you're going to use a cloned APK, rename the system image to _Android/obb/com.briarrose.**clone**/main.30.com.briarrose.**clone**.obb_
3. Install the BRVM APK, run it, wait until the virtual machine is set up
4. Create containers for your games
5. To install the games, copy them to the C: drive within Wine and create shortcuts to their executables 


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

**Elbrus Technologies:** ExaGear

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
