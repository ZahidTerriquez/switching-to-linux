# 🐧 How to Install Ubuntu Linux (Beginner-Friendly Guide)

A complete, step-by-step guide to installing **Ubuntu Linux** — perfect for beginners switching from Windows or macOS.  
Includes downloads, tools, and post-install setup.

---

## 📝 Requirements

- A USB drive (at least 5GB of storage)
- A computer to install Ubuntu on
- Internet access for downloads
- Backup important files before starting!

---

## 🌐 Download Links

- [Etcher (bootable USB tool)](https://etcher.balena.io/)
- [Ubuntu ISO download (desktop version)](https://ubuntu.com/download/desktop)

---

## 🚀 Step 1: Download the Ubuntu ISO

1. Go to [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop).
2. Choose the latest LTS version (recommended).
3. Click **Download** and save the `.iso` file.

---

## 💽 Step 2: Create a Bootable USB Drive

1. Download and install **balenaEtcher**: [https://etcher.balena.io/](https://etcher.balena.io/).
2. Plug in your USB drive.
3. Open Etcher:
   - Click **"Flash from file"** and select your downloaded ISO.
   - Click **"Select target"** and choose your USB drive.
   - Click **"Flash!"** to create the bootable USB.
4. Wait for Etcher to finish and safely eject the USB.

---

## ⚙️ Step 3: Boot from the USB

1. Plug the USB into your target computer.
2. Restart the computer.
3. Access the **BIOS/UEFI** menu (common keys: `Esc`, `Del`, `F2`, `F10`, or `F12`).
4. In BIOS/UEFI:
   - Set your USB drive as the **first boot device**.
   - Save and exit.
5. Your computer should boot from the USB and show the Ubuntu welcome screen.

---

## 🖥️ Step 4: Install Ubuntu

1. At the welcome screen:
   - Choose **"Try Ubuntu"** to test it without installing.
   - Choose **"Install Ubuntu"** to start installation.
2. Follow the prompts:
   - **Keyboard layout**: Select your layout.
   - **Updates and other software**: Choose whether to install updates/third-party software.
   - **Installation type**:  
     - **Erase disk and install Ubuntu** (for a clean install).  
     - **Install alongside Windows** (for dual-boot).  
     - **Something else** (for custom partitions).
3. Enter your username and password.
4. Let the installation complete.
5. Remove the USB and restart your computer.

---

## 🟢 Step 5: Post-Installation Setup

1. Log in to your new Ubuntu system.
2. Open a terminal (`Ctrl+Alt+T`) and update:
   ```bash
   sudo apt update && sudo apt upgrade -y
3. Install essential build tools (many apps require these later):
   ```bash
   sudo apt install build-essential -y
4. Enable the firewall (recommended for security):
    ```bash
    sudo apt install gnome-tweaks -y
6.  Install Git (needed for development and GitHub):
     ```bash
     sudo apt install git -y
7.  Intall a browser (Brave is a good option):
    ```bash
    sudo snap install brave
8.  Reboot after installing everything:
    ```bash
    sudo reboot
    ```
---

Your Ubuntu install is complete, updated, secure, and ready to go — now challenge yourself and start ricing your system with themes, extensions, icons, and layouts to make it truly yours. If this guide helped, drop a ⭐ on the repo!
