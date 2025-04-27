
# Brandon's Linux Tower Starter Kits

Built April 2025 with Caelum

This repository provides two ready-to-deploy Linux setup packages:

## Packages

### 1. Server-Only (Headless) Setup
- File: `master_setup_package_updated.zip`
- Purpose: Sets up a highly optimized Ubuntu Server with no GUI.
- Features: 
  - Netdata Live Dashboard
  - RAM auto-cleaning
  - CPU smart scaling (`schedutil` governor)
  - SSD/NVMe weekly TRIM
  - Automatic security upgrades
- Ideal for towers, servers, headless 24/7 machines.

### 2. Full Desktop + Server Setup
- File: `master_setup_full_gui_package.zip`
- Purpose: Installs full XFCE4 Desktop Environment over Ubuntu Server.
- Features: 
  - All Server-Only optimizations PLUS
  - XFCE Desktop with LightDM login
  - Flameshot Screenshot Tool
  - Flatpak + Flathub enabled
  - GNOME Software Center + Synaptic Package Manager
- Ideal for hybrid server/desktop workstations.

## Quick Start

1. Choose the package that fits your machine (Server-Only or Full Desktop).
2. Transfer the ZIP file to the target machine.
3. Unzip the package:
   ```
   unzip package_name.zip
   ```
4. Enter the extracted folder:
   ```
   cd package_folder
   ```
5. Make the setup script executable:
   ```
   chmod +x setup_script.sh
   ```
6. Run the setup:
   ```
   sudo ./setup_script.sh
   ```
7. (GUI build only) Reboot after install and log into XFCE.

## Notes
- Netdata dashboard is available locally at: `http://YOUR-IP:19999`
- Scripts include automatic service enabling on boot.
- MIT License: Free to use, share, remix.

## Contact

For questions, support, or feedback, contact:

📧 freedomtowerproject@gmail.com

## Built with ❤️ for self-empowerment and community growth.
