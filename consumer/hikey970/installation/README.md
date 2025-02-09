---
title: Installation for HiKey970
permalink: /documentation/consumer/hikey970/installation/
---

# Installation

Choose and install an operating system on your HiKey970. To appropriately follow this installation guide you will need to:

- Choose an installation method
- Download necessary files
- Choose host machine
- Follow flashing instructions

***

## Methods of Installation

In most cases, you will be presented with two options when installing your new operating system onto your HiKey970:

- SD Card Method
- Fastboot Method

Each method has it's own benifits, and requires different levels of experience

### SD Card Method

The SD card method allows you to place a microSD card into a HiKey970 to automatically boot and install an operating system onto the eMMC of your board. This method is generally simpler than other methods and should be used by beginners.

This method requires the following hardware:

- HiKey970 with power supply
- Host machine (Linux, Mac OS X, or Windows)
- MicroSD card with 4GB or more of storage
- USB Mouse and/or keyboard
- HDMI Monitor with full size HDMI cable

Go to the [Downloads page](../downloads/) to get your SD card image.

Choose host machine

- [Linux](linux-sd.md)
- [Mac](mac-sd.md)
- [Windows](windows-sd.md)

***

### Fastboot Method

Fastboot is supported by the board and can be used for installs. This is for advanced users who are most likely modifying/customizing source code and will need to download such updates to the board for test/execution.

This method requires the following hardware:

- HiKey970 with power supply
- Host machine (Linux)
- USB Type-A (Host Machine) to USB Type-C (HiKey970) cable

Go to the [Downloads page](../downloads/) to get your bootloader, boot image, and root file system image (rootfs).

**Choose host machine**

- [Linux](linux-fastboot.md)

***
