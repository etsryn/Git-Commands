# Getting Started with Git

## Introduction
Git is a distributed version control system used to track changes in source code during software development. This document covers the basic setup and fundamental commands to get started with Git.

## 📥 Installing Git
Before using Git, it needs to be installed on your system:

- **Windows:** Download and install from [git-scm.com](https://git-scm.com/downloads)
- **Linux:** Install using package managers (e.g., `sudo apt install git` for Ubuntu)
- **MacOS:** Install via Homebrew (`brew install git`)

## 🔧 Configuring Git
After installation, configure Git with your identity:
```sh
# Set user name
git config --global user.name "Your Name"

# Set email address
git config --global user.email "your.email@example.com"

# Verify configuration
git config --list
```

## 🆕 Initializing a Repository
A Git repository can be created using:
```sh
# Initialize a new Git repository
git init
```

## 📦 Cloning a Repository
To copy an existing repository:
```sh
# Clone a repository
git clone <repository-url>
```

## 📝 Checking the Status
To check the status of your working directory:
```sh
git status
```

## Conclusion
These are the fundamental steps to set up and start using Git. More advanced Git commands and workflows are covered in subsequent sections.
