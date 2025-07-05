# Git and Github cheatsheet

## 🔧 Basic Git Setup

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

```

## 📁 Starting a Project

### Initialize Git

```bash
git init
```
-> Start tracking a local project with Git.

### Clone a GitHub Repository

```bash
git clone <repo-url>
```
-> Download a GitHub repository to your local machine.



## 📝 Making Changes

### Check Status

```bash
git status
```
-> See what’s changed and what’s staged.

### Stage Files

```bash
git add <file>
git add .  # Add all files
```
-> Add files to the staging area.

### Commit Changes

```bash
git commit -m "Your commit message"
```
->Save staged changes with a message.

### View Commit History

```bash
git log
```
-> See list of commits made.


## 🌐 GitHub Remote Commands

### Add Remote Repository

```bash
git remote add origin <repo-url>
```
->Link your local repo to GitHub.

### Push Changes to GitHub
```bash
git push -u origin main  # First time
git push                 # Afterward
```
-> Upload local commits to GitHub.

### Pull Latest Changes
```bash
git pull
```
-> Download and merge changes from GitHub.







