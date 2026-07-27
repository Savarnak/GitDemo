# Git Hands-on Labs

## Overview

This repository contains the Git hands-on exercises completed as part of the Cognizant Digital Nurture Program. Through these labs, I learned the core concepts of Git version control, including repository management, tracking changes, branching, merging, conflict resolution, and synchronization with remote repositories.

---

# Hands-on 1: Git Basics

## Objectives
- Configure Git on a local machine.
- Create and initialize a Git repository.
- Track files using Git.
- Commit changes to the local repository.
- Connect the repository to GitHub.
- Push and pull changes from the remote repository.

## Concepts Learned
- Git installation and configuration
- Git repository initialization (`git init`)
- Working Directory, Staging Area, and Local Repository
- Tracking files using `git add`
- Creating commits using `git commit`
- Checking repository status using `git status`
- Viewing commit history using `git log`
- Adding a remote repository
- Pulling and pushing changes to GitHub

## Commands Practiced

```bash
git --version
git config --global
git init
git status
git add
git commit
git remote add
git pull
git push
```

---

# Hands-on 2: Using .gitignore

## Objectives

- Ignore unnecessary files and folders from version control.

## Concepts Learned

- Purpose of `.gitignore`
- Ignoring file extensions
- Ignoring directories
- Preventing temporary and log files from being tracked

## Implemented

Ignored:

```text
*.log
log/
```

## Commands Practiced

```bash
touch .gitignore
git status
git add
git commit
git push
```

---

# Hands-on 3: Branching and Merging

## Objectives

- Create branches.
- Develop features independently.
- Merge feature branches into the main branch.

## Concepts Learned

- Branch creation
- Branch switching
- Independent development
- Branch comparison
- Fast-forward merge
- Branch deletion

## Commands Practiced

```bash
git branch
git checkout
git branch -a
git diff
git merge
git log --oneline --graph --decorate
git branch -d
```

---

# Hands-on 4: Merge Conflict Resolution

## Objectives

- Understand merge conflicts.
- Resolve conflicts manually.

## Concepts Learned

- How merge conflicts occur
- Conflict markers

```text
<<<<<<< HEAD
=======
>>>>>>>
```

- Manual conflict resolution
- Completing a merge after resolving conflicts
- Updating `.gitignore` after conflict resolution

## Commands Practiced

```bash
git merge
git diff
git status
git add
git commit
```

---

# Hands-on 5: Clean Up and Synchronize with Remote Repository

## Objectives

- Synchronize local and remote repositories.

## Concepts Learned

- Checking repository status
- Listing available branches
- Pulling latest changes
- Pushing local commits
- Verifying synchronization with GitHub

## Commands Practiced

```bash
git status
git branch
git pull origin master
git push origin master
```

---

# Git Concepts Learned

## Repository

A Git repository stores the complete history of project files and their versions.

---

## Working Directory

The folder where files are created and modified.

---

## Staging Area

An intermediate area where changes are prepared before committing.

---

## Local Repository

Stores committed versions of the project on the local machine.

---

## Remote Repository

A GitHub repository used for collaboration and backup.

---

## Branch

An independent line of development that allows multiple features to be developed without affecting the main branch.

---

## Merge

Combines changes from one branch into another.

---

## Merge Conflict

Occurs when the same file is modified differently in multiple branches and Git cannot automatically decide which version to keep.

---

## .gitignore

A configuration file used to exclude files and folders from version control.

Examples:

```text
*.log
log/
*.bak
```

---

# Git Workflow

```
Working Directory
        │
        ▼
git add
        │
        ▼
Staging Area
        │
        ▼
git commit
        │
        ▼
Local Repository
        │
git push / git pull
        │
        ▼
GitHub Remote Repository
```

---

# Skills Acquired

- Git installation and configuration
- Local repository management
- Remote repository integration
- Version control fundamentals
- File tracking
- Commit history management
- Branch creation and management
- Branch merging
- Merge conflict resolution
- Ignoring unnecessary files
- Repository synchronization with GitHub
- Understanding Git workflow
- Basic collaborative development using Git

---

# Repository Link

GitHub Repository:

https://github.com/Savarnak/GitDemo

---

# Outcome

Successfully completed all Git hands-on exercises covering:

- Git Basics
- Git Ignore
- Branching
- Merging
- Merge Conflict Resolution
- Remote Repository Synchronization

These exercises provided practical experience with Git commands and strengthened my understanding of distributed version control systems and collaborative software development workflows.
