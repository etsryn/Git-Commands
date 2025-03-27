# Branching & Merging

## 🌿 Introduction
Branching and merging are key concepts in Git that allow multiple developers to work on different features or bug fixes simultaneously. This document covers essential commands for managing branches and merging changes effectively.

## 📌 Creating and Listing Branches
Create a new branch:
```sh
git branch <branch-name>
```
List all branches:
```sh
git branch
```

## 🔄 Switching Branches
Switch to an existing branch:
```sh
git checkout <branch-name>
```
or (recommended for newer versions of Git):
```sh
git switch <branch-name>
```

## 🛠 Merging Branches
Merge a branch into the current branch:
```sh
git merge <branch-name>
```

## ⚠️ Handling Merge Conflicts
If conflicts arise, manually resolve them in affected files, then commit the changes:
```sh
git add <conflicted-file>
git commit -m "Resolved merge conflict"
```

## 🚀 Deleting Branches
Delete a local branch:
```sh
git branch -d <branch-name>
```
Force delete (if unmerged changes exist):
```sh
git branch -D <branch-name>
```

## Conclusion
Effective branching and merging help maintain a clean and organized workflow. By mastering these commands, you can collaborate efficiently in any Git-based project.
