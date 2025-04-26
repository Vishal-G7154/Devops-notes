# Git & GitHub Notes

This document contains notes about Git commands, workflows, and GitHub usage.

---

## 🛠 What is Git?

- Git is a **Distributed Version Control System (DVCS)**.
- It helps track changes in source code during software development.
- Developers can collaborate without overwriting each other's work.

---

## 🌐 What is GitHub?

- GitHub is a **cloud-based platform** for hosting Git repositories.
- It provides collaboration tools like Pull Requests, Issues, and Actions.

---

## 📦 Basic Git Workflow

1. **git init** → Initialize a new Git repository.
2. **git add .** → Stage all changes.
3. **git commit -m "commit message"** → Commit changes with a message.
4. **git remote add origin <repo-URL>** → Connect to remote repository.
5. **git push -u origin main** → Push local code to GitHub.

---

## 🔥 Important Git Commands


git init
git add .
git commit -m "message"
git remote add origin https://github.com/username/repo.git
git push -u origin main

+++++++++++++++++++++++++++++++

git add .
git commit -m "next commit"
git push



---

## 🧠 Important Concepts

- **Repository (Repo)**: A folder tracked by Git.
- **Commit**: A snapshot of changes.
- **Branch**: A pointer to a specific commit, used for parallel development.
- **Merge**: Combining branches.
- **Clone**: Download a repo from GitHub to local.
- **Push/Pull**: Upload/download code to/from GitHub.

---

## 🧩 GitHub Workflow

1. Fork → Copy someone else's repository.
2. Clone → Download the forked repository locally.
3. Create Branch → Work on a new feature.
4. Commit Changes → Save work locally.
5. Push Branch → Upload branch to GitHub.
6. Pull Request → Request to merge changes into original repository.

---

## 🎯 Best Practices

- Write meaningful commit messages.
- Commit often (small commits).
- Always pull latest changes before pushing.
- Use feature branches instead of committing directly to `main`.
- Resolve merge conflicts carefully.


