# Git Commands Cheatsheet
After you have installed git locally, headover to git bash.

## Git Version

```bash
# Find git version
git --version
```

## Configure Git
 
```bash
# Set user name
git config --global user.name "Your Name"
 
# Set user email
git config --global user.email "your.email@example.com"
```

## Initialize a Repository
 
```bash
git init
```
 
## Clone a Repository
 
```bash
git clone <repository_url>
```
 
## Stage Changes
 
```bash
git add <file(s)>
```
 
## Commit Changes
 
```bash
git commit -m "Your commit message"
```
 
## Check Repository Status
 
```bash
git status
```
 
## View Commit History
 
```bash
git log
```
 
## Create a New Branch
 
```bash
git branch <branch_name>
```
 
## Switch to a Branch
 
```bash
git checkout <branch_name>
```
 
## Merge Branches
 
```bash
git merge <branch_name>
```
 
## Pull Changes from Remote
 
```bash
git pull origin <branch_name>
```
 
## Push Changes to Remote
 
```bash
git push origin <branch_name>
```
 
## Resolve Merge Conflicts
 
```bash
# After conflicts are resolved, add changes and commit
git add <conflicted_file(s)>
git commit -m "Merge conflict resolution"
```
 
## Undo Changes (Discard Local Changes)
 
```bash
git checkout -- <file(s)>
```
 
## Revert to a Previous Commit
 
```bash
git revert <commit_hash>
```
 
## Remove Untracked Files
 
```bash
git clean -fd
```
 
