# Committing & Logging

## 📝 Introduction
Committing changes and maintaining a clear commit history is crucial in Git. This document covers adding files, making commits, and viewing commit history.

## 📂 Staging and Committing Changes
Add a single file:
```sh
git add <file-name>
```
Add all changes:
```sh
git add .
```
Make a commit:
```sh
git commit -m "Your commit message"
```

## 🔍 Viewing Commit History
List commit history:
```sh
git log
```
View commit history in one line:
```sh
git log --oneline
```

## ✏️ Amending Last Commit
Modify the last commit (without changing the commit message):
```sh
git commit --amend --no-edit
```
Modify the last commit message:
```sh
git commit --amend -m "New commit message"
```

## 📌 Checking Differences
View changes in the working directory:
```sh
git diff
```
View differences between commits:
```sh
git diff <commit-hash> <commit-hash>
```

## Conclusion
Keeping a well-structured commit history helps in tracking changes efficiently. These commands ensure proper documentation and tracking of modifications in a project.
