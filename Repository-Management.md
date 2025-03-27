# Repository Management

## 📌 Introduction
Managing repositories efficiently is a fundamental aspect of using Git. This document covers key repository operations such as initialization, cloning, remote management, and synchronization.

## 🏗 Initializing a Repository
To create a new Git repository:
```sh
git init
```
This creates a `.git` directory to store version control information.

## 📂 Cloning a Repository
To copy an existing repository from a remote source:
```sh
git clone <repository-url>
```
Example:
```sh
git clone https://github.com/user/repo.git
```

## 🔗 Managing Remotes
List remote repositories:
```sh
git remote -v
```
Add a new remote:
```sh
git remote add origin <repository-url>
```
Remove a remote:
```sh
git remote remove origin
```

## 🔄 Synchronizing with Remote
Fetch latest changes without merging:
```sh
git fetch
```
Pull latest changes and merge automatically:
```sh
git pull origin main
```
Push local commits to remote:
```sh
git push origin main
```

## Conclusion
Understanding repository management is crucial for efficient Git workflows. Mastering these commands will help in seamless collaboration and version control.
