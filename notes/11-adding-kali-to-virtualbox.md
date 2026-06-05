# 11 - Adding Kali Linux to VirtualBox

## Goal

Add the extracted Kali Linux virtual machine to VirtualBox.

## Files Used

* kali-linux-2026.1-virtualbox-amd64.vbox
* kali-linux-2026.1-virtualbox-amd64.vdi

## What These Files Are

### .vbox

The VirtualBox configuration file that defines the VM settings.

### .vdi

The virtual hard drive containing the Kali Linux installation.

## VM Configuration

* RAM: 4096 MB
* CPUs: 2
* Video Memory: 128 MB
* Network Mode: NAT

## Why NAT

NAT allows the VM to access the internet while keeping the setup simple and isolated.

## What I Learned

Virtual machines consist of both configuration files and virtual disk files. The `.vbox` file tells VirtualBox how to run the machine, while the `.vdi` file stores the operating system and data.
