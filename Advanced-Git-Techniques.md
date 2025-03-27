# Advanced Git Techniques

## 🚀 Introduction
Advanced Git techniques help in refining workflows, managing complex histories, and improving productivity. This document covers interactive rebasing, stashing, cherry-picking, and working with submodules.

## 🔄 Interactive Rebasing
Rebase and edit commit history:
```sh
git rebase -i HEAD~<number-of-commits>
```
To continue after resolving conflicts:
```sh
git rebase --continue
```
To abort an ongoing rebase:
```sh
git rebase --abort
```

## 📌 Stashing Changes
Save uncommitted changes for later:
```sh
git stash
```
List stashed changes:
```sh
git stash list
```
Apply the latest stash:
```sh
git stash apply
```
Remove the latest stash:
```sh
git stash drop
```

## 🍒 Cherry-Picking
Apply a specific commit to the current branch:
```sh
git cherry-pick <commit-hash>
```

## 📦 Working with Submodules
Add a submodule:
```sh
git submodule add <repository-url>
```
Initialize submodules:
```sh
git submodule update --init --recursive
```

## Conclusion
Mastering these advanced Git techniques helps in handling complex workflows, making version control more efficient and flexible.
