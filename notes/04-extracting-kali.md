# 04 - Extracting the Kali Virtual Machine

## Goal

Extract the Kali Linux VirtualBox appliance file.

## Commands Used

```bash
sudo apt install p7zip-full -y
cd ~/Downloads
7z x kali-linux-*.7z

## What I learned

The extracted file is a packaged virtual machine that VirtualBox can import directly.


