# Issue: VM Was Slow and Unresponsive

# Problem

The VM was lagging and very slow after initial installation.

# Cause

- Not enough memory and CPU cores were allocated.
- Default settings (4 GB RAM, 1 CPU) were too low for Windows 10.

# Solution

- Increased memory from 4 GB to **6 GB**.
- Increased CPU from 1 to **2 cores**.
- Enabled "Enable PAE/NX" and VT-x/AMD-V in VirtualBox settings.

# Result

- VM started running smoothly.
- No freezing or long loading times during normal use.
