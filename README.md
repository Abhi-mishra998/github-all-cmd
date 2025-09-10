# GitHub Commands Practice – Merge, Rebase, Stash

## 📌 Overview
This repository is created to practice **essential Git operations** such as:
- Branch creation and switching
- Merge
- Rebase
- Stash
- Commit and push to GitHub

Environment used: **Git Bash on Windows (MINGW64)**

---

## 🛠 Tech Stack
- **Shells**: Git Bash (Windows), WSL, AWS, VirtualBox (Linux)
- **Version Control**: Git & GitHub

---

## ⚡ Branches in This Repo
- `main` → contains stable code and final commits
- `rebase-demo` → used to practice **git rebase**
- `devops-with-abhishek` → used to practice branch creation and commit flow
- *(feature branches were created and merged during practice)*

---

## 🔑 Git Operations Demonstrated

### 1. Merge
```bash
# Create new branch
git checkout -b feature-branch

# Make changes and commit
git add .
git commit -m "Updated script1.sh in feature branch"

# Switch to main and merge
git checkout main
git merge feature-branch
```

### 2. Rebase
```bash
# Create new branch
git checkout -b rebase-demo

# Make changes and commit
git add .
git commit -m "Updated script2.sh in rebase-demo"

# Rebase branch on top of main
git rebase main
```

### 3. Stash
```bash
# Make changes without committing
echo 'Temporary changes' >> script1.sh

# Stash the changes
git stash

# Bring them back
git stash pop
```

---

## 📸 Screenshots
All terminal output and results of each command are captured and included in the PDF report:  
👉  https://github.com/Abhi-mishra998/github-all-cmd/blob/main/all%20github%20cmd.pdf

---

## 🔗 Repository Link
This repository is available publicly at:  
👉 [GitHub Repo – Abhi-mishra998/github-all-cmd](https://github.com/Abhi-mishra998/github-all-cmd)

---

## ✅ Notes
- All tasks were successfully performed and documented.
- Both **code** and **screenshots** are included for verification.
- This repository is created purely for learning purposes.
