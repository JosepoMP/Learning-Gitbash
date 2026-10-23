# ⚡ Git Bash — My Learning Notes

## 📌 About this repository

Welcome to my personal learning notes! 

This repository contains simple guides, commands, and examples about **Git Bash and Git**, organized to help me remember what I learn and practice version control.

> 💡 The goal is simple: learn something new, write it down, and never stop improving.

## 📚 Table of Contents

- [🖥️ Git Bash Guide](#️-git-bash-guide)
- [🔄 Basic Git Workflow](#-basic-git-workflow)
- [📖 Commands Cheat Sheet](#-commands-cheat-sheet)
- [🚀 My Learning Journey](#-my-learning-journey)

---

## 🖥️ Git Bash Guide

### 1. 📂 Navigate through folders

Before working on a project, we need to find the folder where our files are located.

```bash
ls
```
Lists the files and folders in the current directory.

```bash
cd folder-name
```
Enters the selected folder.

```bash
cd ..
```
Goes back to the parent folder.

### 2. 📥 Clone a repository

Copy the repository URL from GitHub and use the following command:

```bash
git clone repository-url
```

This downloads a copy of the repository to your computer.

### 3. 📁 Enter the project folder

After cloning the repository, navigate into its folder:

```bash
cd project-name
```

### 4. 💻 Open the project in VS Code

```bash
code .
```

Opens the current project folder in Visual Studio Code.

*Note: VS Code must be installed, and the `code` command must be available in your terminal.*

### 5. ➕ Stage your changes

Before committing, select the files you want Git to include in the next commit:

```bash
git add README.md src/Bienvenida.java
```

You can also stage all changes in the current repository with:

```bash
git add .
```

### 6. 📸 Save a commit

Create a commit with a short message describing your changes:

```bash
git commit -m "docs: notas"
```

A commit saves a snapshot of the staged changes in your local Git history.

### 7. 🚀 Push changes to GitHub

Finally, upload your local commits to the remote repository:

```bash
git push origin main
```

Your changes will appear on GitHub once the push succeeds.

---

## 🔄 Basic Git Workflow

The usual workflow for saving and uploading changes is:

```text
1. Edit your files
      ↓
2. git status
      ↓
3. git add .
      ↓
4. git commit -m "your message"
      ↓
5. git push origin main
      ↓
6. Check your repository on GitHub
```

## 📖 Commands Cheat Sheet

| Command | What it does |
|---|---|
| `ls` | Lists files and folders |
| `cd folder-name` | Enters a folder |
| `cd ..` | Goes back one folder |
| `git clone URL` | Clones a repository |
| `code .` | Opens the current folder in VS Code |
| `git status` | Shows the current state of the repository |
| `git add .` | Stages all changes |
| `git commit -m "message"` | Creates a commit |
| `git push origin main` | Pushes commits to the `main` branch |

## 🚀 My Learning Journey

- [x] Learn basic navigation commands.
- [x] Clone a GitHub repository.
- [x] Open projects using VS Code.
- [x] Stage, commit, and push changes.
- [ ] Learn how to create branches.
- [ ] Learn how to merge branches.
- [ ] Practice resolving merge conflicts.
- [ ] Learn how to work with pull requests.

---

<p align="center">
  <b>Q divertido</b>
</p>
