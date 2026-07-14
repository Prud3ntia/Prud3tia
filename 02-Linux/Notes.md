# Linux Fundamentals
# NetworkChuck – Linux Basics

## Lesson Objective

Learn what Linux is, understand the Linux file system, and become familiar with essential terminal commands.

---

# What is Linux?

Linux is **not** an operating system.

Linux is a **kernel**, which is the core of an operating system.

Operating systems built using the Linux kernel are called **Linux distributions (distros)**.

Examples:

- Ubuntu
- Debian
- Kali Linux
- Parrot OS
- Fedora

---

# Parrot OS

Parrot OS is a Linux distribution designed for:

- Cybersecurity
- Ethical hacking
- Penetration testing
- Privacy

Like Kali Linux, it is built on top of the Linux kernel.

---

# Open Source

Linux is open source.

This means anyone can:

- View the source code
- Modify it
- Distribute it

Benefits:

- Free
- Secure through community review
- Highly customizable

---

# Graphical User Interface (GUI)

GUI (Graphical User Interface) allows users to interact with Linux using windows, icons, and menus instead of only using commands.

Examples:

- GNOME
- KDE Plasma
- XFCE

---

# Everything is a File

One of Linux's most important concepts is:

> **Everything is treated like a file.**

Examples:

- Network settings
- Hard drives
- Devices
- System configuration
- Commands

This makes Linux very flexible and powerful.

---

# Linux File System

## /

The root directory.

Everything on the system begins here.

---

## /bin

**Binary**

Contains essential user commands.

Examples:

- ls
- cp
- mv
- cat

---

## /sbin

**System Binary**

Contains administrative commands.

Usually requires root privileges.

---

## /etc

Contains system configuration files.

Examples:

- Network configuration
- User settings
- Service configuration

---

# Basic Linux Commands

## pwd

**Print Working Directory**

Displays your current location.

Example:

```bash
pwd
```

---

## ls

**List**

Displays files and folders inside the current directory.

Example:

```bash
ls
```

---

## cd

**Change Directory**

Moves between folders.

Example:

```bash
cd Documents
```

---

## cd ..

Moves up one directory.

Example:

```bash
cd ..
```

---

## whoami

Displays the current logged-in user.

Example:

```bash
whoami
```

---

## clear

Clears the terminal screen.

Example:

```bash
clear
```

Shortcut:

```
Ctrl + L
```

---

## cat

**Concatenate**

Displays the contents of a file.

Example:

```bash
cat notes.txt
```

---

## cp

**Copy**

Copies files or directories.

Example:

```bash
cp file1.txt file2.txt
```

---

## sudo

Temporarily runs one command with administrator (root) privileges.

Example:

```bash
sudo apt update
```

---

## rm

Removes (deletes) files.

Example:

```bash
rm notes.txt
```

Be careful:

`rm` permanently deletes files.

---

## which

Shows the location of a command.

Example:

```bash
which python3
```

Output:

```
/usr/bin/python3
```

**Important**

`which` **does NOT** tell you which user you are.

Use:

```bash
whoami
```

to display the current user.

---

# Commands Learned

- pwd
- ls
- cd
- cd ..
- whoami
- clear
- Ctrl + L
- cat
- cp
- sudo
- rm
- which

---

# Key Takeaways

- Linux is a kernel, not an operating system.
- Parrot OS and Kali Linux are Linux distributions.
- Linux is open source.
- Everything in Linux is treated as a file.
- The root directory is `/`.
- `/bin` contains essential commands.
- `/sbin` contains administrative commands.
- `/etc` stores system configuration files.
- Learning terminal commands is the foundation of Linux.

---

# Cybersecurity Connection

Linux is the most common operating system used by:

- Ethical hackers
- Penetration testers
- Security analysts
- Servers
- Cloud environments

Learning Linux is one of the most important skills in cybersecurity.

---

# AI Connection

Many AI systems run on Linux because it is:

- Stable
- Fast
- Customizable
- Well-supported by Python and AI frameworks like PyTorch and TensorFlow
