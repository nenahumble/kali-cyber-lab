# 17 - Installing Basic Lab Tools

## Overview

The next step in building the cyber lab was to install and verify commonly used Linux and cybersecurity tools.

## Commands Used

```bash
sudo apt update
sudo apt install -y git tree htop curl wget
```

## Tools Installed

### Git

Used for version control and managing project repositories.

### Tree

Used to visualize directory structures from the command line.

### htop

Provides an interactive view of running processes and system resource usage.

### curl

Used to transfer data and interact with web services from the command line.

### wget

Used to download files directly from the command line.

## Challenges Encountered

While following the planned installation steps, I discovered that the `neofetch` package was not available in the current Kali repositories.

This provided a good reminder that software availability can change between operating system versions and that documentation should be adapted to reflect actual results rather than expected results.

## Wireshark Verification

Verified that Wireshark was already installed on the Kali virtual machine.

```bash
wireshark --version
```

Result:

* Wireshark 4.6.6

## What I Learned

Kali Linux includes many cybersecurity tools by default. It is important to verify whether a tool is already installed before attempting to install it manually.

I also learned that package availability can change over time, requiring flexibility and troubleshooting during system administration tasks.
