# 16 - Configuring VirtualBox Integration Features

## Overview

After successfully setting up Kali Linux, I configured several VirtualBox integration features to improve usability and make file sharing between the host and virtual machine easier.

## Goal

Improve the workflow between the Ubuntu host system and the Kali Linux virtual machine.

## Features Configured

### VirtualBox Guest Additions

Installed VirtualBox Guest Additions to improve compatibility between Kali Linux and VirtualBox.

Benefits include:

* Improved display support
* Dynamic screen resizing
* Better mouse integration
* Improved overall VM experience

### Shared Clipboard

Enabled bidirectional clipboard sharing between the host and virtual machine.

This allows text to be copied and pasted between Ubuntu and Kali Linux.

### Drag and Drop

Enabled bidirectional drag-and-drop support for transferring files between systems.

### Shared Folder

Created a shared folder named:

```text
CyberLabShare
```

The folder was successfully mounted inside Kali Linux as:

```text
/media/sf_CyberLabShare
```

## Verification

Verified that the shared folder was accessible from within Kali Linux and could be used to transfer files between the host and virtual machine.

## Why This Is Important

These integration features make it easier to move files, notes, scripts, screenshots, and lab resources between the host operating system and the virtual machine.

This creates a more efficient workflow when working on cybersecurity projects and lab exercises.

## What I Learned

VirtualBox integration features help bridge the gap between the host operating system and the guest virtual machine. Proper integration improves productivity and makes lab management significantly easier.
