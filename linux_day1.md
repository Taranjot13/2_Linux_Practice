# Linux Practice – Day 1

## Basic Commands Practiced:
- pwd
- ls
- cd
- mkdir linux_practice
- cd linux_practice
- touch file1.txt
- mkdir subfolder
- mv file1.txt subfolder/
- ls subfolder
- cat, nano, clear, history

# 🌐 Git + Linux Practice (WSL + GitHub)

## ✅ Git Setup & Workflow (Completed)

🔧 Git Configuration
```bash
git config --global user.name "Taranjot Singh"
git config --global user.email "65taranjot@gmail.com"

🐙 Repository Setup
cd ~/Desktop/CLOUD/2_Linux_Practice
git init
git remote add origin git@github.com:Taranjot13/2_Linux_Practice.git

🔐 SSH Key Generation & GitHub Connection
ssh-keygen -t ed25519 -C "65taranjot@gmail.com"
cat ~/.ssh/id_ed25519.pub
# Add to GitHub → Settings → SSH & GPG keys → New SSH key

🚀 Push to GitHub using SSH
git add .
git commit -m "Initial commit"
git push -u origin main

