# 10 - Extracting the Kali Linux Image

## Goal

Extract the downloaded Kali Linux VirtualBox image.

## Downloaded File

kali-linux-2026.1-virtualbox-amd64.7z

## Commands Used

```bash
sudo apt install p7zip-full -y
cd ~/Downloads
7z x kali-linux-2026.1-virtualbox-amd64.7z
```

## Result

The archive extracted successfully and created a Kali Linux VirtualBox machine directory.

## Why Extraction Is Necessary

The download is compressed to reduce file size. The VM files must be extracted before VirtualBox can load them.

## What I Learned

VirtualBox virtual machines can be distributed as compressed archives containing configuration files and virtual disk files.
