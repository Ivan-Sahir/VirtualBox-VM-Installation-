# Creating a Windows 10 Virtual Machine in VirtualBox

This document outlines the process for setting up a Windows 10 VM in VirtualBox.


# Steps to Create the VM

1. **Download ISO**
   - Official Windows 10 ISO from Microsoft.

2. **VirtualBox Settings**
   - **Name**: `Win10-Test`
   - **Type**: Microsoft Windows
   - **Version**: Windows 10 (64-bit)

3. **Resources Allocated**
   - Memory: 4096 MB
   - CPU: 2 cores
   - Video Memory: 128 MB
   - Disk: 50 GB (VDI, dynamically allocated)

4. **Mount ISO**
   - In VirtualBox → Settings → Storage → Controller: IDE → Load ISO

5. **Start Installation**
   - Booted VM and installed Windows 10 normally.
   - Installed Guest Additions.

6. **Post-Install**
   - Performed Windows Updates.
