# The Mira Project
The Mira Project is a set to tools that grants you more power and control over your jailbroken Playstation 4. It is the result of all the  hard work by the OpenOrbis team.

It works differently to the custom firmware experience on Playstation 3, where CFW would be installed on the system via modified PUP files (e.g. Rebug), however once the framework is installed and ran it gives users the same functionality they were previously used to.

### Firmware
Formerly known as MiraHEN, this has now been developed into a full custom firmware.

### Tools
#### newlib-ps4
This is the libc implementation ported for PS4. As it is extremely difficult to compile for PS4, we recommend using the pre-built binaries instead.

#### ld-ps4
This is the linker to be used with newlib-ps4 to create Orbis compatible ELF files. Alternatively, you can use CrazyVoid's elfFixupTool.

#### MiraLib
This is the communications library that will be specialized for operation with the Mira firmware.

#### PS4 Payload Sender
A simple Android application to send payloads to your PS4.

### Plugins
The Mira Project offers two types of plugins: built-in plugins and external plugins. Default plugins are embedded inside Mira firmware and include file transfer, a log server and a debugger. External plugins can be loaded from internel/external HDD, for example PS4 Linux Loader.

#### PS4 Linux Loader
A simple plugin that lets you run the Linux kernel from a remote device without webkit.

## User Guide
The users guide can be found at [USERS.md](https://github.com/OpenOrbis/mira-project/blob/master/USERS.md). This guide should be followed if you require instructions on how to build, install and use the firmware once it is installed on the console.

## Developer Guide
You will need VS2017, with Linux plugin and WSL (Ubuntu on Windows) or a physical Linux machine or Linux VM to be able to build the project. More details about the build process will be posted here shortly.

## Special Thanks
We want to give a special shout out to these people in no particular order.

* flatz
* SpecterDev
* EvilSperm
* Rogero
* Joonie
* AlexAltea
* Mistawes
* Abkarino
* qwertyoruiop
* CTurT
* Mathieulh
* Senaxx
* m0rph3us1987
* CrazyVoid
* xvortex
* bigboss
* ZeraTron
* xorloser
* AlAzif
* masterzorag
* fail0verflow
* idc
* valentinbreiz
* Anonymous Contributors (You know who you are)
