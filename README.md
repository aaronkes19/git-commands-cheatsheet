# Basic Git Commands Cheatsheet

## Setup
- `git config --global user.name "Your Name"`
- `git config --global user.email "your@email.com"`

## Starting a Repo
- `git init` → Initialize a new Git repository
- `git clone <url>` → Clone an existing repository

## Staging & Committing
- `git status` → Show changes
- `git add <file>` → Stage a file
- `git commit -m "Message"` → Commit staged changes

## Branching
- `git branch` → List branches
- `git branch <name>` → Create new branch
- `git checkout <name>` → Switch branch
- `git merge <branch>` → Merge branch into current

## Remote
- `git remote -v` → Show remotes
- `git push origin <branch>` → Push changes
- `git pull origin <branch>` → Pull changes

## Undo
- `git reset --hard HEAD` → Reset to last commit
- `git checkout -- <file>` → Discard changes in file
