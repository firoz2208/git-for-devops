# Git Commands Reference

## Git Installation
- Install Git using winget:
  winget install --id Git.Git -e --source winget

## Git Configuration
- Configure your Git email:
  git config --global user.email "firoz.ace@gmail.com"
- Configure your Git username:
  git config --global user.name "firozshaikh"

## Git Initialization
- Initialize a Git repository:
  git init

## Working with Files
- Create a new directory:
  mkdir git-for-devops
- Change directory:
  cd git-for-devops/
- Create a new file:
  vim hello.txt
- Display file contents:
  cat hello.txt
- List files in a directory:
  ls

## Git Status and Log
- Check the current status of your repository:
  git status
- View the commit log:
  git log
- View the commit log in one line:
  git log --oneline

## Adding and Committing Changes
- Add a specific file to staging:
  git add hello.txt
- Add all changes to staging:
  git add .
- Commit changes with a message:
  git commit -m "Commit message here"

## Branching and Switching
- Create and switch to a new branch:
  git checkout -b dev
- Switch to an existing branch:
  git switch dev
- Switch back to the main branch:
  git checkout main

## Viewing Branches
- List all branches:
  git branch

## Miscellaneous
- View command history:
  history
- Display a tree structure of the repository:
  tree
- Check the directory you're in:
  pwd
