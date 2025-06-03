# 🐧 How to Install Linux Ubuntu

A step-by-step guide to installing Ubuntu Linux on your computer.

---

## 📝 Requirements

- A USB drive (at least **5GB** of storage)
- A computer to install Ubuntu on
- Internet access for downloads
- Backup important files before starting!

---

## 🌐 Download Links

- [Etcher (for creating bootable USB)](https://etcher.balena.io/)
- [Ubuntu ISO download](https://ubuntu.com/download/desktop)

---

## 🚀 Step 1: Download the Ubuntu ISO

1. Go to [https://ubuntu.com/download/desktop](https://ubuntu.com/download/desktop).
2. Choose the latest LTS version or the version you prefer.
3. Click **Download** and save the ISO file.

---

## 💽 Step 2: Create a Bootable USB Drive

1. Download and install **balenaEtcher**: [https://etcher.balena.io/](https://etcher.balena.io/).
2. Plug in your USB drive.
3. Open Etcher:
   - Click **"Flash from file"** and select your downloaded ISO.
   - Click **"Select target"** and choose your USB drive.
   - Click **"Flash!"** to create the bootable USB.
4. Safely eject your USB when done.

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
