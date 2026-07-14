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


Absolutely. These are **Anki-quality flashcards** for your **NetworkChuck Linux Basics** lesson. They focus on understanding the concepts, not just memorization.

---

# 📚 Flashcards – Linux Basics (NetworkChuck)

---

### Card 1

**Q:** What is Linux?

**A:** Linux is a **kernel**, not an operating system.

---

### Card 2

**Q:** What is a kernel?

**A:** The core of an operating system that manages hardware and allows software to communicate with it.

---

### Card 3

**Q:** What is a Linux distribution (distro)?

**A:** An operating system built on the Linux kernel.

Examples:

* Kali Linux
* Parrot OS
* Ubuntu
* Debian
* Fedora

---

### Card 4

**Q:** Is Parrot OS a Linux distribution?

**A:** Yes.

---

### Card 5

**Q:** Why is Linux popular in cybersecurity?

**A:**

* Open source
* Highly customizable
* Powerful command line
* Widely used on servers and security tools

---

### Card 6

**Q:** What does open source mean?

**A:** The source code can be viewed, modified, and distributed by anyone.

---

### Card 7

**Q:** What is a GUI?

**A:** Graphical User Interface.

Allows users to interact using windows, icons, and menus instead of only commands.

---

### Card 8

**Q:** What is one of the most important concepts in Linux?

**A:** Everything is treated like a file.

---

### Card 9

**Q:** Give three examples of things Linux treats as files.

**A:**

* Devices
* Network settings
* Configuration files

---

### Card 10

**Q:** What does `/` represent?

**A:** The root directory.

Everything starts here.

---

### Card 11

**Q:** What does `/bin` contain?

**A:** Essential binary (command) programs.

Examples:

* ls
* cp
* cat

---

### Card 12

**Q:** What does `/sbin` contain?

**A:** Administrative system commands.

---

### Card 13

**Q:** What does `/etc` contain?

**A:** System configuration files.

---

### Card 14

**Q:** What does `pwd` stand for?

**A:** Print Working Directory.

---

### Card 15

**Q:** What does `pwd` do?

**A:** Displays your current directory.

---

### Card 16

**Q:** What does `ls` do?

**A:** Lists files and folders.

---

### Card 17

**Q:** What does `cd` stand for?

**A:** Change Directory.

---

### Card 18

**Q:** What does `cd ..` do?

**A:** Moves up one directory.

---

### Card 19

**Q:** What does `whoami` do?

**A:** Displays the currently logged-in user.

---

### Card 20

**Q:** What does `clear` do?

**A:** Clears the terminal screen.

---

### Card 21

**Q:** What keyboard shortcut also clears the terminal?

**A:** Ctrl + L

---

### Card 22

**Q:** What does `cat` stand for?

**A:** Concatenate.

---

### Card 23

**Q:** What does `cat` do?

**A:** Displays the contents of a file.

---

### Card 24

**Q:** What does `cp` do?

**A:** Copies files or folders.

---

### Card 25

**Q:** What does `sudo` do?

**A:** Runs a command with administrator (root) privileges.

---

### Card 26

**Q:** What does `rm` do?

**A:** Permanently removes files or directories.

---

### Card 27

**Q:** What does `which` do?

**A:** Shows the location of a command.

Example:

```bash
which python3
```

---

### Card 28

**Q:** Which command tells you your current user?

**A:** `whoami`

---

### Card 29

**Q:** Which command tells you where a command is installed?

**A:** `which`

---

### Card 30

**Q:** Why is learning Linux important for cybersecurity?

**A:** Most servers, cloud systems, hacking tools, and cybersecurity environments run on Linux.

---

# ⭐ Must Memorize

These are the highest-yield cards from this lesson:

| Command  | Purpose                 |
| -------- | ----------------------- |
| `pwd`    | Print current directory |
| `ls`     | List files              |
| `cd`     | Change directory        |
| `cd ..`  | Go up one directory     |
| `whoami` | Current user            |
| `clear`  | Clear terminal          |
| `cat`    | Display file contents   |
| `cp`     | Copy files              |
| `rm`     | Remove files            |
| `sudo`   | Run as administrator    |
| `which`  | Find command location   |

---

## 🚀 Linux Command Challenge (No Notes)

See if you can answer these from memory:

1. Which command tells you where you are?
2. Which command lists files?
3. Which command changes directories?
4. Which command takes you up one folder?
5. Which command tells you who you're logged in as?
6. Which command shows where Python is installed?
7. Which command displays a file's contents?
8. Which command copies a file?
9. Which command deletes a file?
10. Which command gives temporary administrator privileges?


---

