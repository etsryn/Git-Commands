# Undoing Changes & Fixing Mistakes

## 🔄 Introduction
Mistakes happen, and Git provides powerful ways to undo changes, revert commits, and recover lost work. This document covers essential commands to manage and fix mistakes efficiently.

## 🚫 Discard Unstaged Changes
To discard changes in a specific file:
```sh
git checkout -- <file-name>
```
To discard all unstaged changes:
```sh
git reset --hard
```

## 🔄 Unstage Files
To remove files from the staging area without deleting them:
```sh
git reset <file-name>
```
To unstage all files:
```sh
git reset
```

## ⏪ Reverting Commits
To undo the last commit while keeping changes:
```sh
git reset --soft HEAD~1
```
To completely remove the last commit:
```sh
git reset --hard HEAD~1
```

## 🔙 Reverting a Pushed Commit
To create a new commit that undoes the changes of a previous commit:
```sh
git revert <commit-hash>
```

## 🚀 Recovering Deleted Files
To restore a deleted file before committing:
```sh
git checkout -- <file-name>
```
To restore after committing:
```sh
git checkout <commit-hash> -- <file-name>
```

## Conclusion
Understanding how to undo changes and recover from mistakes is crucial for maintaining a clean and efficient Git workflow.
