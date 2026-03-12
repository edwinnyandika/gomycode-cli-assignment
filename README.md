# 🖥️ Git Bash CLI Assignment

> Fundamental filesystem operations mastered through the command line — no GUI used at any point.

**Edwin Nyandika** · GO MY CODE Software Development Bootcamp

---

## 📌 About This Project

This project documents the completion of a CLI (Command Line Interface) assignment from the GO MY CODE Software Development Bootcamp. The objective was to perform core filesystem operations exclusively through the terminal using **Git Bash** on Windows and **Termux** on Android.

No file explorer. No right-click menus. No GUI tools. Just the terminal.

This assignment covers the foundational CLI skills every developer needs before working with Git, servers, cloud infrastructure, and deployment pipelines.

---

## 📁 Project Structure

```
~/GOMYCODE/
└── first-repo/
    ├── edwin.txt        ← Created with first name (Task 05)
    ├── index.html       ← Renamed from index.md, contains "Hello World" (Task 08)
    └── README.md        ← Copied from index.html (Task 09)
```

---

## ✅ Tasks Completed

| # | Task | Command Used |
|---|------|-------------|
| 01 | Created `GOMYCODE` folder in home directory | `mkdir GOMYCODE` |
| 02 | Created `first-repo` inside `GOMYCODE` | `mkdir first-repo` |
| 03 | Created a `.txt` file with last name | `touch nyandika.txt` |
| 04 | Deleted the file | `rm nyandika.txt` |
| 05 | Created a `.txt` file with first name | `touch edwin.txt` |
| 06 | Created `index.md` | `touch index.md` |
| 07 | Wrote `"Hello World"` into `index.md` | `echo "Hello World" > index.md` |
| 08 | Renamed `index.md` to `index.html` | `mv index.md index.html` |
| 09 | Copied `index.html` to `README.md` | `cp index.html README.md` |

---

## 🛠️ Tools Used

- **Git Bash** — Bash shell emulator for Windows (via Git for Windows)
- **Termux** — Linux terminal emulator for Android
- **Git** — Version control to track and push this project to GitHub

---

## 💻 Commands Reference

```bash
cd ~                        # Go to home directory
cd foldername               # Enter a folder
cd ..                       # Go up one level
mkdir foldername            # Create a new folder
touch filename              # Create an empty file
ls                          # List directory contents
rm filename                 # Permanently delete a file
echo "text" > file          # Write text into a file
cat filename                # Display file contents
mv oldname newname          # Rename or move a file
cp source destination       # Copy a file
pwd                         # Show current directory path
```

---

## 🚀 How to Run Locally

If you want to replicate this assignment on your own machine:

**On Windows (Git Bash):**
```bash
# Install Git for Windows from https://git-scm.com
# Open Git Bash and run:
cd ~
mkdir GOMYCODE
cd GOMYCODE
mkdir first-repo
cd first-repo
```

**On Android (Termux):**
```bash
# Install Termux from F-Droid: https://f-droid.org/packages/com.termux/
# Open Termux and run:
pkg update && pkg upgrade
pkg install git
cd ~
mkdir GOMYCODE
cd GOMYCODE
mkdir first-repo
cd first-repo
```

Then follow the 9 tasks listed in the table above.

---

## 🌐 Live Site

The documentation for this assignment is hosted on GitHub Pages:

**👉 [View Live Site](https://gomycode-cli-assignment.vercel.app/)**

---

## 📖 What I Learned

- How to navigate the filesystem entirely through the CLI
- The difference between `mv` (rename/move) and `cp` (copy)
- How the `>` redirect operator writes output into files
- Why developers prefer CLI over GUI for speed and automation
- How the terminal prompt reflects your current working directory
- How to initialize a Git repository and push to GitHub from the CLI

---

## 👤 Author

**Edwin Nyandika**
GO MY CODE Software Development Bootcamp
GitHub: [@edwinnyandika](https://github.com/edwinnyandika)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

*Built with curiosity, patience, and a lot of `ls` commands.* 🌱
