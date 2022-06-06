---
marp: true
theme: gaia
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
