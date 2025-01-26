# Linux and Git Commands

## Basic Navigation
- **Print Current Directory:** `pwd`
- **List Files:** `ls`
- **Change Directory:** `cd <directory>`
- **Go Back One Directory:** `cd ..`

## File and Directory Management
- **Create Directory:** `mkdir <directory>`
- **Remove Directory:** `rmdir <directory>`
- **Create File:** `touch <filename>`
- **Remove File:** `rm <filename>`
- **Copy File/Directory:** `cp <source> <destination>`
- **Move/Rename File/Directory:** `mv <source> <destination>`

## File Content Operations
- **View File Content:** `cat <filename>`
- **Edit File (Nano):** `nano <filename>`
- **Edit File (Vim):** `vi <filename>`
- **Append Text to File:** `echo <text> >> <filename>`
- **Overwrite File Content:** `echo <text> > <filename>`

## File Permissions
- **Change File Permissions:** `chmod <permissions> <filename>`

## SSH and SCP
- **Connect to Server:** `ssh -i <keyfile> user@host`
- **Copy File to Server:** `scp -i <keyfile> <localfile> user@host:<remotepath>`

## Git Commands

### Setup
- **Set Global Username:** `git config --global user.name "<name>"`
- **Set Global Email:** `git config --global user.email "<email>"`

### Repository Management
- **Initialize Repository:** `git init`
- **Check Repository Status:** `git status`
- **View Commit Log:** `git log`
- **View Commit Log (One Line):** `git log --oneline`

### Branch Management
- **Create New Branch:** `git checkout -b <branch>`
- **Switch Branch:** `git checkout <branch>`
- **List Branches:** `git branch`

### Staging and Committing
- **Add File to Staging Area:** `git add <filename>`
- **Add All Files:** `git add .`
- **Commit Changes:** `git commit -m "<message>"`

### File Management in Git
- **Remove File from Staging Area:** `git rm --cached <filename>`
- **Restore Deleted File:** `git restore <filename>`
