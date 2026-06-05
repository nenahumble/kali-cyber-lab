# 08 - Installing VirtualBox on the New Host

## Overview

I moved my Kali Cyber Lab project to a different computer and needed to rebuild the lab environment from the beginning.

Rather than viewing this as lost progress, I used the opportunity to document the setup process more thoroughly and practice rebuilding the environment from scratch.

## Host System Information

### Operating System

Ubuntu 24.04.4 LTS

### CPU

AMD Ryzen 7 5700U with Radeon Graphics

### Memory

16 GB RAM

## Goal

Install VirtualBox and prepare the system for a Kali Linux virtual machine.

## Commands Used

```bash
sudo apt update
sudo apt upgrade -y
sudo apt install virtualbox virtualbox-ext-pack -y
```

## Result

VirtualBox installed successfully and launched without issues.

## Challenges Encountered

During the initial setup on a previous system, I encountered virtualization conflicts involving KVM and VirtualBox. This experience helped me better understand how Linux virtualization technologies interact.

## What I Learned

* VirtualBox allows operating systems to run in isolated virtual machines.
* Understanding host system resources helps determine appropriate VM settings.
* Rebuilding an environment is valuable practice and improves troubleshooting skills.
* Good documentation makes it easier to recreate environments in the future.

## Next Steps

* Download Kali Linux VirtualBox image
* Import Kali into VirtualBox
* Configure VM resources
* Complete first boot
* Begin building the cybersecurity lab environment
