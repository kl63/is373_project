---
title: "Install Ubuntu on a Mac: A Quick Guide"
---

![Ubuntu for mac screenshot](/images/ubuntuformac.jpg)

**Ubuntu** is an open-source operating system popular for development. Installing it on a Mac allows you to dual-boot or switch between macOS and Ubuntu, enhancing flexibility for development work.

## Prerequisites

- A Mac with macOS
- **USB drive (8GB+)**
- **Ubuntu ISO** from [here](https://ubuntu.com/download/desktop)
- **Balena Etcher** for creating a bootable USB

## Installation Steps

### 1. Create a Bootable USB

1. Download the **Ubuntu ISO**.
2. Use **Balena Etcher** to flash the ISO to a USB drive.

### 2. Partition Mac Drive

1. Open **Disk Utility**.
2. Create a new partition (20 GB+) in **MS-DOS (FAT)** format.

### 3. Boot from USB

1. Restart the Mac and hold **Option (⌥)** key during boot.
2. Select the USB drive from the boot menu.

### 4. Install Ubuntu

1. Choose **Try Ubuntu** from the USB boot.
2. Select **Install Ubuntu** and follow the prompts.
3. Install Ubuntu on the new partition.

### 5. Dual Boot Setup

1. After installation, hold **Option (⌥)** on restart to choose between macOS and Ubuntu.

For easier dual-booting, consider installing **rEFInd** from [here](https://www.rodsbooks.com/refind/).

## Post-Installation

- Run system updates:
  ```bash
  sudo apt update && sudo apt upgrade