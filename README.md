# Munjez Releases

Welcome to the official releases repository for **Munjez**, a premium, cross-platform productivity and task management suite. This repository hosts compiled binaries, installers, and updater metadata for Windows, Linux, and Android.

---

## Quick Links
* 🏠 [Official Website](https://munjez-website.vercel.app/)
* 💻 [Source Code (Private Repository)](https://github.com/Osama2214/todo-app-munjez-v1.4)
* 👨‍💻 [Developer Portfolio](https://osama-portfolio-six.vercel.app/)

---

## Download Munjez

Get the latest stable release of Munjez for your operating system:

### Windows (Recommended)
Download the interactive, custom-branded installer:
* **[Download Munjez Setup (.exe)](https://github.com/Osama2214/munjez-releases/releases/latest/download/Munjez_Installer.exe)**

### Linux
Choose the package format suitable for your distribution:
* **[Download AppImage (Portable)](https://github.com/Osama2214/munjez-releases/releases/latest/download/munjez.AppImage)** - Run on any distribution.
* **[Download Debian Package (.deb)](https://github.com/Osama2214/munjez-releases/releases/latest/download/munjez.deb)** - For Ubuntu, Debian, Mint.
* **[Download RPM Package (.rpm)](https://github.com/Osama2214/munjez-releases/releases/latest/download/munjez.rpm)** - For Fedora, RHEL, openSUSE.

### Android
Get the mobile app companion:
* **[Download Android APK (.apk)](https://github.com/Osama2214/munjez-releases/releases/latest/download/munjez.apk)**

---

## Installation Guides

### Windows Installation Guide
1. Download **`Munjez_Installer.exe`** from the link above.
2. Double-click the installer to launch the custom Munjez Setup wizard.
3. Follow the onscreen instructions to install the application.

> ⚠️ **Note on Windows SmartScreen:** Because this app is self-published and does not contain a paid commercial EV certificate, Windows Defender SmartScreen might show a warning ("Windows protected your PC"). 
> * **To proceed:** Click **"More Info"** and then click **"Run anyway"**. The app is completely safe and free.

---

### Linux Installation Guide
* **For AppImage:**
  1. Download the `.AppImage` file.
  2. Right-click the file, go to *Properties* -> *Permissions*, and check **"Allow executing file as program"** (or run `chmod +x munjez.AppImage` in your terminal).
  3. Double-click the file to launch Munjez.
* **For Debian/Ubuntu (.deb):**
  ```bash
  sudo dpkg -i munjez.deb
  sudo apt-get install -f # Install dependencies if required
  ```

---

### Android Installation Guide
1. Download the `.apk` file directly on your Android device.
2. Tap the file to install it.
3. If prompted, enable **"Install from unknown sources"** in your browser or file manager settings to complete the installation.

---

## Auto-Updater System
Munjez features an integrated auto-updater for desktop platforms. 
* The application periodically checks this repository's releases for the `latest-windows.json` metadata file.
* If a new version is detected, Munjez will prompt you to update and will securely download and apply the update in the background.
