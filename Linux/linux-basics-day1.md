# Linux Basics - Day 1

## Introduction to UNIX

UNIX is a multi-user, multitasking operating system developed in the 1970s. It laid the foundation for many modern operating systems, including Linux and macOS.

### Features
- Multi-user
- Multitasking
- Stable
- Secure
- Command-line interface

---

# Introduction to Linux

Linux is a free and open-source UNIX-like operating system kernel created by **Linus Torvalds** in **1991**.

## Popular Linux Distributions
- Kali Linux
- Ubuntu
- Debian
- Fedora
- Arch Linux

## Why Linux is Popular in Cybersecurity
- Open Source
- Secure
- Powerful Terminal
- Networking Tools
- Penetration Testing Support

---

# Virtual Machine

A virtual machine (VM) allows multiple operating systems to run on a single physical computer.

Examples:
- VMware Workstation
- Oracle VirtualBox

---

# Installing Kali Linux

Basic Steps:
1. Download the Kali Linux ISO.
2. Create a new virtual machine.
3. Attach the ISO file.
4. Start the virtual machine.
5. Complete the installation.
6. Update the system.

---

# Linux File System Architecture

Everything in Linux starts from the Root Directory.

```
/
```

## Important Directories

### /
Root directory containing the entire Linux file system.

### /home
Stores personal files and folders of normal users.

Example:
```
/home/username
```

### /root
Home directory of the root (administrator) user.

### /etc
Contains system configuration files.

### /var
Contains variable data such as:
- Log files
- Cache files
- Mail
- Database files

### /bin
Essential user commands.

Examples:
- ls
- cp
- mv
- cat

### /sbin
System administration commands.

### /usr
User applications and utilities.

### /tmp
Temporary files.

### /dev
Device files.

### /boot
Boot loader files and the Linux kernel.

---

# Difference Between /home and /root

| /home | /root |
|--------|--------|
| Home directory for normal users | Home directory for the root user |
| Accessible by users | Reserved for the administrator |

---

# Interview Questions

### What is UNIX?
A multi-user, multitasking operating system that inspired Linux.

### What is Linux?
A free and open-source UNIX-like operating system kernel.

### Who created Linux?
Linus Torvalds (1991).

### What is the root directory?
The top-level directory represented by `/`.

### What is stored in `/etc`?
System configuration files.

### What is stored in `/var`?
Logs, caches, mail, and other variable data.

### What is the difference between `/home` and `/root`?
`/home` stores normal users' files, while `/root` is the administrator's home directory.

---

# Summary

- UNIX inspired Linux.
- Linux is open source.
- Everything starts from the root directory (`/`).
- `/home` stores user files.
- `/root` belongs to the administrator.
- `/etc` stores configuration files.
- `/var` stores logs and variable data.
- Linux is widely used in cybersecurity.
