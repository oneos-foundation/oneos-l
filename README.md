# OneLinux OS

**OneLinux OS** is an experimental minimal Linux operating system built from scratch using **Buildroot**.  
The project was developed inside a Docker container and is bootable via **QEMU**.  

---

## Overview

OneLinux OS demonstrates how to:

- Build a custom Linux root filesystem  
- Install and configure a bootloader (`extlinux` / `syslinux`)  
- Create bootable disk images  
- Test kernels in a virtual environment  

It is intended primarily for **educational purposes** and experimentation with Linux internals.

---

## Features

- Minimal Linux system based on Buildroot  
- Bootable via MBR and Syslinux  
- Runs inside QEMU with GUI or console  
- Fully contained in a disk image (`.img`)  
- Planned experimental package manager (`packmgr`)  

---

## Goals

- Provide a simple, reproducible environment for learning Linux boot process  
- Allow testing of custom kernels and root filesystems  
- Serve as a foundation for lightweight experimental OS projects  

---

## Notes

- The project is **experimental** and not intended for production use  
- Designed for **learning and testing** rather than daily tasks  
- Encourages understanding of bootloaders, kernel loading, and minimal OS design  

****
