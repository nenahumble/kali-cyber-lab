# 14 - Updating Kali Linux

## Overview

After successfully booting Kali Linux, I updated the operating system to ensure it had the latest security patches, bug fixes, and software updates.

## Commands Used

```bash
sudo apt update
sudo apt full-upgrade -y
sudo reboot
```

## What These Commands Do

### sudo apt update

Downloads the latest package information from configured repositories so the system knows what updates are available.

### sudo apt full-upgrade -y

Installs available updates and allows packages to be upgraded, removed, or replaced if necessary to complete the upgrade process.

### sudo reboot

Restarts the system to ensure all updates are fully applied.

## Why Updating Is Important

Keeping systems updated helps protect against known security vulnerabilities and software bugs. Updates often contain security patches that address weaknesses discovered after software is released.

## Security Considerations

Outdated software can contain vulnerabilities that attackers already know how to exploit. Regular updates reduce the risk of compromise by ensuring security fixes are applied as they become available.

## What I Learned

Maintaining a secure system is an ongoing process. Applying updates is one of the most basic but important security practices because it helps protect against known threats and improves system stability.

