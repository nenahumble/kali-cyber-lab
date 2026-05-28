# 07 - First Kali Linux Setup

## Goal

Perform the initial Kali Linux setup after the first successful boot.

## Commands Used

```bash
sudo apt update && sudo apt full-upgrade -y
sudo apt install -y virtualbox-guest-x11
sudo reboot
```

## What Guest Additions Improved

- Dynamic screen resizing
- Better mouse integration
- Improved graphics support
- Better VirtualBox integration

## Snapshot Created

Name:
Fresh Kali Install

## Why Snapshots Matter

Snapshots allow me to restore the VM to a known working state if I break something during testing or experimentation.

## What I Learned

Virtual machine snapshots are extremely useful for cybersecurity labs because they make experimentation much safer.
