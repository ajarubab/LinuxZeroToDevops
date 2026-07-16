
# Linux to DevOps - Day 01

This repository contains the basic Linux, Git, and VS Code setup commands required to start a DevOps journey.

---

## 1. Update System Packages

Update the package index.

```bash
sudo apt update
```

---

## 2. Install Git

Install Git on Ubuntu.

```bash
sudo apt install git -y
```

Verify installation:

```bash
git --version
```

---

## 3. Check VS Code Installation

Verify whether VS Code is installed.

```bash
code --version
```

---

## 4. Check Snap Version

Snap is used to install applications like VS Code.

```bash
snap version
```

---

## 5. Install Visual Studio Code

Install VS Code using Snap.

```bash
sudo snap install code --classic
```

---

## 6. Check Current Directory

Display the current working directory.

```bash
pwd
```

---

## 7. Create Project Directory

Create a new directory for your DevOps practice.

```bash
mkdir ~/linuxZeroToDevops
```

---

## 8. Open Project in VS Code

Navigate into the project and open it.

```bash
cd ~/linuxZeroToDevops
code .
```

---

## 9. Initialize Git Repository

Create a new Git repository.

```bash
git init
```

---

## 10. Configure Git Username

Set your Git username.

```bash
git config --global user.name "Your Name"
```

---

## 11. Configure Git Email

Set your Git email.

```bash
git config --global user.email "youremail@example.com"
```

---

## 12. Verify Git Configuration

Display the current Git configuration.

```bash
git config --list
```

---

## 13. Add Remote Repository

Connect your local repository to GitHub.

```bash
git remote add origin https://github.com/username/repository.git
```

Check remote URL:

```bash
git remote -v
```

---

## 14. Create Main Branch

Rename the default branch to `main`.

```bash
git branch -M main
```

---

## 15. Create README File

Create a README file.

```bash
touch README.md
```

---

## 16. Check Repository Status

View modified and untracked files.

```bash
git status
```

---

## 17. Stage Files

Stage all files for commit.

```bash
git add .
```

---

## 18. Commit Changes

Save changes in Git history.

```bash
git commit -m "Initial project setup"
```

---

## 19. Push Code to GitHub

Upload the code to GitHub.

```bash
git push -u origin main
```

---

# Technologies Used

- Ubuntu 26.04 LTS
- Git
- GitHub
- Visual Studio Code

---

# Author

**Raja Kumar Prasad**
