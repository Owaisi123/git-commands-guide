# Git Commands Guide

This repository contains essential Git commands with explanations to help developers efficiently manage their projects using Git.

## Getting Started with Git

### 1. Check Git Version
```sh
git --version
```
_Checks the installed Git version._

### 2. Initialize a New Repository
```sh
git init
```
_Creates a new Git repository in the current directory._

### 3. Configure Git User
```sh
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```
_Sets your global Git username and email._

### 4. View Git Configuration
```sh
git config --list
```
_Lists all configured Git settings._

## Working with Changes

### 5. Check Repository Status
```sh
git status
```
_Shows the current state of the repository, including untracked and modified files._

### 6. Add Files to Staging
```sh
git add <file1> <file2>
```
_Adds specific files to the staging area._
```sh
git add .
```
_Adds all changes to the staging area._

### 7. Commit Changes
```sh
git commit -m "Your commit message"
```
_Creates a new commit with the staged changes._

## Viewing History

### 8. View Commit History
```sh
git log
```
_Displays a list of previous commits with details._
```sh
git log --oneline
```
_Shows commit history in a compact format._

## Branching and Merging

### 9. List Branches
```sh
git branch
```
_Shows all local branches._

### 10. Create a New Branch
```sh
git branch <branch-name>
```
_Creates a new branch without switching to it._

### 11. Switch to a Branch
```sh
git switch <branch-name>
```
_Switches to an existing branch._

### 12. Create and Switch to a New Branch
```sh
git switch -c <branch-name>
```
_Creates a new branch and switches to it._

### 13. Merge a Branch
```sh
git merge <branch-name>
```
_Merges the specified branch into the current branch._

### 14. Rebase a Branch
```sh
git rebase <branch-name>
```
_Reapplies commits from the current branch onto the specified branch._

### 15. Cherry-Pick a Commit
```sh
git cherry-pick <commit-id>
```
_Applies a specific commit from another branch._

### 16. Rename a Branch
```sh
git branch -m <old-branch-name> <new-branch-name>
```
_Renames an existing branch._

### 17. Delete a Branch
```sh
git branch -d <branch-name>
```
_Deletes a branch if it is merged._
```sh
git branch -D <branch-name>
```
_Force deletes a branch, even if it is not merged._

## Uploading to GitHub

### 18. Connect to a Remote Repository
```sh
git remote add origin <repository-url>
```
_Links the local repository to a GitHub repository._

### 19. Push Changes to GitHub
```sh
git push -u origin main
```
_Uploads the local commits to the GitHub repository._

### 20. Pull Latest Changes from GitHub
```sh
git pull origin main
```
_Fetches and merges the latest changes from the remote repository._

## Conclusion
This guide covers fundamental Git commands for efficient version control. Keep practicing and exploring Git to improve your workflow!

