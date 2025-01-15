# File 2

- This is a sample file for the demo.

### Demo Overview

- In this demo, we will be learning about the following topics:
  - Git Basics
  - Git Commands
  - Git Branches
  - Git Stash
  - Git Ignore
  - Git Branching
  - Git Rebase
  - Git Squashing

### Removing Branches from local which are deleted from remote

- There is no straight forward way to do this.
- We have to manually remove the branches from local.
- We can use the following command to remove the branches from local:
  - `git branch -d <branch-name>`
  - `git branch -D <branch-name>`

### Removing a file from Github tracking (Incase it is pushed to remote and we want to remove it from remote)

- We can use the following command to remove the file from Github tracking:
  - `git rm --cached <file-name>`
