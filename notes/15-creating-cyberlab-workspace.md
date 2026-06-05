# 15 - Creating a Cyber Lab Workspace

## Overview

To keep the Kali Linux virtual machine organized, I created a dedicated workspace directory structure for future cybersecurity projects, scripts, tools, notes, and packet captures.

## Goal

Create a centralized location for storing lab-related files and resources.

## Commands Used

```bash
mkdir -p ~/Lab/{Projects,Scripts,Tools,Captures,Notes}
```

To verify the directory structure:

```bash
tree ~/Lab
```

## Directory Structure

```text
Lab
├── Projects
├── Scripts
├── Tools
├── Captures
└── Notes
```

## Purpose of Each Directory

### Projects

Stores cybersecurity projects, labs, and practice exercises.

### Scripts

Stores Bash, Python, and automation scripts created during learning and testing.

### Tools

Stores downloaded tools, utilities, and supporting software.

### Captures

Stores packet captures, network traces, and other collected data.

### Notes

Stores personal notes, observations, and documentation related to lab activities.

## Challenges Encountered

While creating the directory structure, I initially received a shell parsing error due to incorrect brace expansion syntax. After reviewing the command and correcting the formatting, the directories were created successfully.

## What I Learned

Organizing a lab environment early helps keep projects and tools manageable as the lab grows. I also learned how Linux brace expansion can be used to create multiple directories with a single command.
