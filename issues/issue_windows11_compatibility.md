# Issue: Unable to Install Windows 11 Due to System Requirements

# Problem

I tried to install Windows 11 in VirtualBox but the installation failed with an error about system compatibility.

# Cause

- Windows 11 requires features like TPM 2.0 and Secure Boot.
- VirtualBox doesn’t fully support these features on all hardware.

# Solution

- Switched to installing **Windows 10** instead, which is fully supported.
- Windows 10 runs well in VirtualBox with standard settings.
- This allowed me to proceed with my cybersecurity and firewall testing projects.

