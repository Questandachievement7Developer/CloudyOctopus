# :sparkles: freestadia :sparkles: 
A project that started privately that heavily inspired by Google Stadia allowing to play games or use Desktop through any browser that supported html5 (Yes even your fridge) hosted through your main computer easily (relatively speaking) 
## This Project is built upon these core Components
- VNC
- noVNC
- SPICE
- VirGL
- PulseAudio
- Wine
- Xserver (of course)
- HTML5 ,JS
- Proot and more!
> no wonder my computer crashes when i run this
## Since this is really in early development however there are several Things to be considered not working yet
- Audio
- Peripherals Controller Forwarding
## and these are the unknown or untested part
- Fullscreen mousebinding

However if you still presist and want to taste the development version you could install by Following these instruction

# Requirements
- Archlinux based OS
- an internet Connection
- A real GPU with Real connected monitor
- Disk space at least 64GB
- Linux Kernel at least 4.19 above

## Steps to install
1. Get the file on local computer either
  * Git clone it with
```
git clone https://github.com/Questandachievement7Developer/freestadia
```
  * Download zip using Clone or download button on Right side
  * Download static Script file from releases tabs ( unavailable )
2. Create user.txt on the folder ( the example content of the user.txt should be like this) Do not use spaces or numbers on their name
```
Robert
Okarima
Njordlant
```
3. Launch the Script
```
sh servermanager
```
4. It will prompt you a password just type any password what you wanted
5. Wait
6. Finished

# Servermanager Additional Commands
1. Launch Normally
```
sh servermanager
```
2. Stop Server
```
sh servermanager stop
```
3. Reset Server data ( This will delete user data )
```
sh servermanager reset
```
4. Reinstall All System user (This wont delete userdata)
```
sh servermanager reinstall_alluser
```
5. Restart Users in the Server
```
sh servermanager restart
```
6. Crash the server?
```
sh servermanager oops
```
7. Create a dummy profile to test and develop profiles
```
sh servermanager test
```
8. Update all Users system
```
sh servermanager updatesync
```
9. Mount all containers without launching it
```
sh servermanager mountdev
```
## Thats it Remember its still in Development Stage
