# 🐧 Linux Basics – Cheat Sheet

## 📌 Introduction to Linux
- Linux is a free and open-source UNIX-like operating system.
- Popular distributions: Ubuntu, Fedora, Debian, Arch, CentOS.

## 🔧 File System Structure
| Directory | Description |
|-----------|-------------|
| `/`       | Root directory |
| `/home`   | User directories |
| `/bin`    | Essential user binaries |
| `/etc`    | Configuration files |
| `/var`    | Logs and variable files |
| `/usr`    | User-installed software |
| `/tmp`    | Temporary files |
| `/root`   | Root user's home |

---

## 📂 File & Directory Commands

| Command | Description |
|--------|-------------|
| `pwd` | Show current directory |
| `ls` | List files/directories |
| `ls -l` | Long listing format |
| `cd` | Change directory |
| `cd ..` | Go one directory back |
| `mkdir folder_name` | Create a directory |
| `rmdir folder_name` | Remove empty directory |
| `rm -r folder_name` | Remove non-empty directory |
| `touch file.txt` | Create empty file |
| `cp file1.txt file2.txt` | Copy file |
| `mv old.txt new.txt` | Rename/move file |
| `rm file.txt` | Delete file |
| `clear` | Clear terminal |

---

## 🧑‍💻 User & Permissions

| Command | Description |
|--------|-------------|
| `whoami` | Show current user |
| `sudo command` | Run command as superuser |
| `chmod +x file.sh` | Make file executable |
| `chmod 755 file` | Change permissions |
| `chown user:group file` | Change file ownership |
| `passwd` | Change user password |

---

## 📄 File Content Commands

| Command | Description |
|--------|-------------|
| `cat file.txt` | Show file content |
| `head -n 10 file.txt` | First 10 lines |
| `tail -n 10 file.txt` | Last 10 lines |
| `less file.txt` | Scroll through file |
| `nano file.txt` | Edit file in terminal |
| `echo "Hello" > file.txt` | Write text to file |
| `echo "More" >> file.txt` | Append to file |

---

## 🔍 Search & Find

| Command | Description |
|--------|-------------|
| `find . -name "*.txt"` | Find files |
| `grep "word" file.txt` | Search word in file |
| `grep -r "word" .` | Recursive search |

---

## 📦 Package Management (Ubuntu/Debian)

| Command | Description |
|--------|-------------|
| `sudo apt update` | Update repo info |
| `sudo apt upgrade` | Upgrade packages |
| `sudo apt install package` | Install |
| `sudo apt remove package` | Uninstall |
| `apt list --installed` | List installed packages |

---

## 🔗 Networking

| Command | Description |
|--------|-------------|
| `ifconfig` | Show IP info (needs `net-tools`) |
| `ip a` | Show IP info (modern) |
| `ping google.com` | Test connectivity |
| `curl example.com` | Fetch web content |
| `wget url` | Download file |

---

## 🧠 System Info

| Command | Description |
|--------|-------------|
| `uname -a` | Kernel info |
| `top` or `htop` | Live system processes |
| `df -h` | Disk usage |
| `du -sh folder/` | Folder size |
| `free -h` | RAM usage |
| `uptime` | System uptime |
| `history` | Show command history |

---

## 🗃️ Process Management

| Command | Description |
|--------|-------------|
| `ps` | List processes |
| `ps aux` | Detailed process list |
| `kill PID` | Kill process |
| `kill -9 PID` | Force kill |

---

## 🧪 Bash Scripting (Intro)

```bash
#!/bin/bash
echo "Hello, $USER"
date
