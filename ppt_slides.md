---
marp: true
theme: gaia
author: Minh Diep
---
# Git Basics
Git is used to track changes to code and to synchronize code with other people. 
#### Some Basic Git Commands
- $ git clone <url>: make a copy of an existing repository in a different location/directory. 
- $ git add <filename>: add a file to track changes within that file.
- $ git commit -m "message": commit a change with a message.
- $ git commit -am "message": commit all the files that have been changed.
___
#### Some Basic Git Commands (continued)
- $ git status: display what is going on inside the git.
    - ex: what changes have not been committed, etc. 
- $ git push: push the new commit to Github.
- $ git pull: take the newest changes for the latest version on Github to the version in our computer. 
- $ git log: display the history of changes/commits have been made. 
- $ git reset: convert to the previous state of change. 
___
# Merge Conflicts
Merge conflicts happen changes are made to the same part of the same file on two different branches. _There are merge conflict markers to show you where the conflict happened._
#### General steps to resolve merge conflicts
1. Check to see if there is a conflict and look for where it occurs (using pull request & markers).
2. Make a final change to that part & delete markers. 
3. Commit change. 
___
# Merge Conflicts Markers
- This is an example of merge conflict markers

![width:1000px height:10cm](img_3.png)
___
# Branching
A method of moving into a new direction when creating a new feature, and only combining this new feature with the main branch, once you’re finished. 
#### Implementing branching in git repo
- $ git branch: see which branch you're currently working on.
- $ git checkout -b <name>: create a new branch. 
- $ git checkout <name>: switch between branches.
- Commit any changes to each branch and merge the branches using $ git merge <other branch name>. 
___
# Additional GitHub Features
1. Forking: creates a copy of any repository that you have access to and this copy is owned by you.
2. Pull Requests: requests for new changes to be added to the main version of the repository. 
3. GitHub Pages: a way to publish a static website to the web.