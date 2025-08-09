# EmbeddedPoCs – Proof of Concepts for Embedded Linux & IoT

**Author:** Ankur Rastogi  
**Email:** arlinuxiot2020@gmail.com  
**LinkedIn:** [linkedin.com/in/AnkurEmb.Consultant](https://www.linkedin.com/in/a-r-69ab381a9/)  
**GitHub:** [AnkurEmb.Consultant](https://github.com/ankurhcl)  

---

## 📦 Overview

This repository contains a **collection of Proof-of-Concepts (PoCs)** demonstrating my capabilities in Embedded Linux, Board Support Package (BSP) development, diagnostics, networking, and bootloader customization.  
Each PoC folder is a self-contained, minimal yet functional example designed to showcase a specific service area I offer as a consultant.

The **`EmbeddedPoCs.zip`** file contains the complete directory structure and code for all PoCs listed below.

---

## 📂 PoC List & Descriptions

| PoC Folder | Technology / Tools | Description |
|------------|--------------------|-------------|
| **bash-auto-debug-scripts** | Bash | Auto-run hardware debug scripts for GPIO, Ethernet, I²C, USB checks. |
| **bash-hardware-diagnostics-suite** | Bash | CPU, memory, storage, and temperature diagnostic scripts for embedded targets. |
| **board-bringup-notes-imx8** | Yocto / DTS / Bash | Bring-up logs, device tree, GPIO test scripts for i.MX8-based boards. |
| **bootloader-customization-demo** | U-Boot, Secure Boot | Example of U-Boot config changes, FIT image creation, and secure boot signing. |
| **c-api-utils-linux** | C | GPIO HAL layer and example CLI app for Linux systems. |
| **initramfs-launcher-demo** | Initramfs | Minimal initramfs launcher with boot log and config. |
| **linux-char-driver-template** | Linux Kernel | Template for creating a simple character device driver. |
| **linux-net-scan-tools** | Bash / C | Ping sweep, TCP port scanner, and network interface monitor. |
| **openwrt-board-bringup-demo** | OpenWrt / UCI | OpenWrt bring-up example with init scripts, UCI network defaults, and device tree overlay. |
| **uboot-env-config-demo** | U-Boot | Environment variable customization and FIT image template. |
| **yocto-custom-layer-rpi** | Yocto | Custom Yocto layer for Raspberry Pi with image recipe and postboot script. |
| **zephyr-basic-apps** | Zephyr RTOS | GPIO toggle and UART echo sample apps with west.yml project setup. |

---

## 🚀 How to Use

1. **Download** the ZIP from this repository.
2. Extract the contents:
   ```bash
   unzip EmbeddedPoCs.zip
