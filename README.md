# RAID Drivers for Windows Installation

This repository contains the RAID drivers for both Intel and non-Intel based systems, packaged as .inf files. These drivers are essential for the installation of Windows, especially when the installation process requests specific drivers to be found.

## Usage Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/GurucharanSavanth/Windows-RAID-Drivers-for-windows.git
   cd Windows-RAID-Drivers-for-windows

2. **Copy Drivers to USB Drive**:
   - Download the required RAID driver files from this repository.
   - Copy the files to a USB drive.

3. **Windows Installation**:
   - During the Windows installation process, when prompted to find drivers, insert the USB drive.
   - Select the "Browse" option.
   - Uncheck the "Hide" option to ensure all driver files are visible.
   - Navigate through the USB drive and select the appropriate .inf file (generally, select `nvme.inf` file).

## Included Files

- `nvme.inf`
- Other RAID drivers for both Intel and non-Intel systems.

## Support

For any issues or questions, please open an issue in this repository.

---

**Note**: Make sure to select the correct driver for your specific hardware configuration to ensure a smooth installation process.
