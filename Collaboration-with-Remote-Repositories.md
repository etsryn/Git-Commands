# Collaboration with Remote Repositories

## 🔗 Introduction
Git enables seamless collaboration by allowing multiple developers to work on a project using remote repositories. This document covers pushing, pulling, fetching, and handling conflicts.

## 📤 Pushing Changes
Upload local commits to a remote repository:
```sh
git push origin <branch-name>
```
Force push (use with caution):
```sh
git push --force
```

## 📥 Pulling Changes
Fetch and merge changes from a remote repository:
```sh
git pull origin <branch-name>
```

## 🔄 Fetching Changes
Retrieve changes without merging:
```sh
git fetch
```
Compare fetched changes:
```sh
git diff origin/<branch-name>
```

## ⚠️ Resolving Merge Conflicts
If conflicts occur after pulling changes, manually resolve them in affected files, then:
```sh
git add <conflicted-file>
git commit -m "Resolved merge conflict"
```

## 🔄 Reverting a Push
Undo the last push (if necessary):
```sh
git revert HEAD
```

## Conclusion
Collaborating with remote repositories ensures smooth teamwork in Git projects. Understanding these commands helps in effective version control and conflict resolution.
