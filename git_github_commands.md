# Git and Github cheatsheet

## 🔧 Basic Git Setup

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"

```

## 📁 Starting a Project

### ✅ Initialize Git

```bash
git init
```
➡️ Start tracking a local project with Git.

### ✅ Clone a GitHub Repository

```bash
git clone <repo-url>
```
➡️ Download a GitHub repository to your local machine.



## 📝 Making Changes

### ✅ Check Status

```bash
git status
```
➡️ See what’s changed and what’s staged.

### ✅ Stage Files

```bash
git add <file>
git add .  # Add all files
```
➡️ Add files to the staging area.

### ✅ Commit Changes

```bash
git commit -m "Your commit message"
```
➡️ Save staged changes with a message.

### ✅ View Commit History

```bash
git log
```
➡️ See list of commits made.

---

## 🌐 GitHub Remote Commands

### ✅ Add Remote Repository

```bash
git remote add origin <repo-url>
```
➡️ Link your local repo to GitHub.

### ✅ Push Changes to GitHub

```bash
git push -u origin main  # First time
git push                 # Afterward
```
➡️ Upload local commits to GitHub.

### ✅ Pull Latest Changes

```bash
git pull
```
➡️ Download and merge changes from GitHub.

---

## 🔁 Branching

### ✅ Create a new branch

```bash
git branch <branch-name>
```

### ✅ Switch to a branch

```bash
git checkout <branch-name>
```

### ✅ To rename a branch

```bash
git branch - M main
```

### ✅ Create and switch to new branch

```bash
git checkout -b <branch-name>
```
➡️ Use branches to develop features separately.

### ✅ Merge a branch into main

```bash
git checkout main
git merge <branch-name>
```
➡️ Combines changes from another branch into main.

### ✅ Delete a branch

```bash
git branch -d
```



---

## 🧹 Clean Up

### ✅ Remove a file from staging

```bash
git reset <file>
git reset
```

### ✅ Undo last commit (keep changes)

```bash
git reset --soft HEAD~1
git reset HEAD~1
```

### ✅ Undo upto a specific commit(for many commits)

```bash
git reset <-commit hash->
git reset--hard <-commit hash->
```

### ✅ Delete a branch

```bash
git branch -d <branch-name>
```

---

## 🔄 Sync with GitHub

### ✅ Change remote URL

```bash
git remote set-url origin <new-url>
```

### ✅ Check current remotes

```bash
git remote -v
```

--- 

## 🧪 Viewing Differences

## ✅ Show file changes

```bash
git diff
```

## ✅ Show changes in staged files

```bash
git diff --staged
```

---

## 📦 Ignore Files

### ✅ .gitignore

➡️ Create a file named .gitignore and add file/folder names to exclude them from Git:

```bash
venv/
__pycache__/
*.log
```

---

## 💥 Dangerous but Useful

### ✅ Delete all local changes (careful!)

```bash
git checkout -- <file>
```
### ✅ Hard reset to last commit

```bash
git reset --hard HEAD
```

---

## 🧑‍🤝‍🧑 Collaboration

### ✅ Fork a repo on GitHub:

1 ➡️ Click "Fork" on GitHub.

2 ➡️ Clone your forked repo.

3 ➡️ Make changes, push, then make a pull request.

```bash
git clone <your-fork-url>                          # -> Clone your fork
git push origin <branch-name>                      # -> Push your changes
```

---

## 📦 Stashing Changes

### ✅ Stash Uncommitted Work

```bash
git stash
```

### ✅ Apply Stashed Changes

```bash
git stash pop
```

---

## ✅ Must open example workflow
<details>
<summary> ✅ Example Workflow </summary>

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/user/repo.git
git push -u origin main

```

</details>

---


# 👨‍💻 Happy Coding! | ⭐ Star the repo if this helped!











