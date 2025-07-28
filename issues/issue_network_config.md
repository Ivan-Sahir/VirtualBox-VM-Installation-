# Issue: Network Not Working / Same IP Confusion

# Problem 1

After using **NAT**, the VM could access the internet but couldn't be pinged or scanned from the host.

# Explanation
- With NAT networking, the VM can access the internet, but the host and other devices on the local network cannot directly communicate with the VM because NAT hides the VM behind the host’s IP.

# Solution
- Switched network mode to **Bridged Adapter**.
- Selected the **correct physical adapter** (Wi-Fi in my case).

# Problem 2

Public IP shown in browser on random website was the same on host and VM.

# Explanation
- Both devices use the same router, so they share the same public IP.
- Local IPs (e.g., 192.168.x.x) are what matter for testing.

# Solution
- Verified with `ipconfig` inside host and VM to ensure **unique local IPs**.

# Result

- Bridged networking allowed host <--> VM communication.
- Could now test firewall rules, ping between machines, and simulate attacks.
