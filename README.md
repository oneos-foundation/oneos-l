# OneOS

**OneOS** is an experimental minimal Linux operating system built from scratch using **Buildroot**.  
The project is developed inside a Docker container and bootable via **QEMU**.  

---

## Overview

OneOS demonstrates how to:

- Build a custom Linux root filesystem  
- Install and configure a bootloader (`extlinux` / `syslinux`)  
- Create bootable disk images  
- Test kernels in a virtual environment  

It is intended primarily for **educational purposes** and OS experimentation.

---

## Features

- Minimal Linux system based on Buildroot  
- Bootable via MBR and Syslinux  
- Runs inside QEMU with GUI or console  
- Fully contained in a disk image (`.img`)  
- Planned experimental package manager (`packmgr`)  

---

## Goals

- Provide a simple environment for learning the Linux boot process  
- Allow testing of custom kernels and root filesystems  
- Serve as a foundation for lightweight experimental OS projects  

---

## Notes

- **Experimental project**, not for production use  
- Designed for **learning and testing**, not daily tasks  
- Helps understand bootloaders, kernel loading, and minimal OS design  
