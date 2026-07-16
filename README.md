# Linux to DevOps


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

# Linux to DevOps - Day 02

---

## 1. Check Current Working Directory

Displays the current location in the file system.

```bash
pwd
```

Example Output:

```text
/home/rk
```

---

## 2. List Files and Directories

Lists all files and directories in the current location.

```bash
ls
```

Example Output:

```text
Desktop  Documents  Downloads  Music  Pictures  Videos
linuxZeroToDevops
```

---

## 3. Change Directory

Move into the Documents directory.

```bash
cd Documents
```

Verify the location:

```bash
pwd
```

Output:

```text
/Users/rk/Documents
```

---

## 4. Go to Root Directory

```bash
cd /
pwd
```

Output:

```text
/
```

---

## 5. Go to Home Directory

```bash
cd ~
pwd
```

Output:

```text
/home/rk
```

---

## 6. View Hidden Files

List all files including hidden files.

```bash
ls -al
```

Some hidden files:

- `.bashrc`
- `.bash_history`
- `.gitconfig`
- `.ssh`

---

## 7. Navigate to Project Directory

| `ls` | List files and folders |
| `ls -al` | Show detailed list including hidden files |
```bash
cd linuxZeroToDevops
ls
```

Output:

```text
README.md
```

---

## 8. Return to Home Directory

```bash
cd
```

---

## 9. Move to Parent Directory

```bash
cd ..
```

Moves one level up.

---

## 10. Move Multiple Levels Up

```bash
cd ../..
```

Moves two levels up in the directory hierarchy.

---

## Topic: Linux `ls` Command Practice

---

## 1. List Files and Directories

The `ls` command displays the contents of the current directory.

```bash
ls
```

**Example Output**

```text
Desktop  Documents  Downloads  Music  Pictures  Public
Templates  Videos  linuxZeroToDevops  snap
```

---

## 2. Long Listing Format

Displays detailed information about files and directories.

```bash
ls -l
```

It shows:

- File permissions
- Number of links
- Owner
- Group
- File size
- Last modified date
- File/Directory name

---

## 3. Human Readable Format

Displays file sizes in a human-readable format (KB, MB, GB).

```bash
ls -lh
```

Example:

```text
4.0K
```

instead of

```text
4096
```

---

## 4. Show Hidden Files

Lists all files, including hidden files.

```bash
ls -la
```

Hidden files start with a dot (`.`), for example:

- `.bashrc`
- `.bash_history`
- `.gitconfig`
- `.profile`
- `.ssh`

---

## 5. Sort by Modification Time

Displays files sorted by their last modified time.

```bash
ls -ltr
```

Options used:

- `-l` → Long listing
- `-t` → Sort by modification time
- `-r` → Reverse order (oldest first)

| `ls` | List files and folders |
| `ls -al` | Show detailed list including hidden files |
---

## 6. Recursive Listing

Lists all files and subdirectories recursively.

```bash
ls -R
```

Example:

```text
Pictures/
└── Screenshots/
    └── Screenshot From 2026-07-16 09-35-25.png

linuxZeroToDevops/
└── README.md
```

---
# Commands Learned

| Command | Purpose |
|----------|---------|

| `pwd` | Show current directory |
| `cd directory` | Change directory |
| `cd ..` | Move to parent directory |
| `cd /` | Move to root directory |
| `cd ~` | Move to home directory |
| `cd` | Return to home directory |

| `ls` | List files and directories |
| `ls -l` | Long listing format |
| `ls -lh` | Human-readable file sizes |
| `ls -la` | Show hidden files with details |
| `ls -ltr` | Sort by modification time (oldest first) |
| `ls -R` | List files recursively |

---


# Technologies Used

- Ubuntu 26.04 LTS
- Git
- GitHub
- Visual Studio Code

---

# Author

**Raja Kumar Prasad**
