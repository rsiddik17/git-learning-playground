# Git Learning Playground 🏗️

This repository contains a roadmap for learning Git step by step, from basics to advanced.  
It can be used as a personal note or a quick reference (cheatsheet).

---

## 1. Git Basics

**Config**
- git config --global user.name "Your Name"
- git config --global user.email "you@example.com"
- git config --global --list

**Initialize a repository**
- git init
- git clone <url>

**Add & save changes**
- git add .        # all files
- git add <file>   # specific file
- git commit -m "message"

**Check status & logs**
- git status
- git log
- git log --oneline --graph

**View differences**
- git diff
- git diff --staged

**Undo simple changes**
- git restore <file>
- git reset <file>

## 2. Remote Repository

**Add a remote**
- git remote add origin <url>
- git remote -v

**Push to remote**
- git branch -M main
- git push -u origin main
- git push

**Pull & fetch**
- git pull
- git fetch
- git pull origin main

## 3. Branching Workflow

**Create & switch branches**
- git branch
- git checkout -b feature-x
- git switch -c feature-x
- git switch main

**Merge a branch**
- git merge
- git merge feature-x

**Delete / rename branch**
- git branch -d feature-x
- git branch -m new-name

**Delete a branch on remote**
- git push origin --delete <branch>

**View all branches**
- git branch -r
- git branch -a

**Rebase**
- git rebase