---
layout: page
title: Gitlet
description: A version-control system that has the same commands as Git, but with an additional command (find)
img: assets/img/project_gitlet/github.png
importance: 5
category:
---

Gitlet is a version-control system that mimics some of the basic features of  Git. 

##### Gitlet can:
1. Save the contents of entire directories of files.
2. Restore a version of one or more files or entire commits. 
3. View the history of your backups. 
4. Maintain related sequences of commits
5. Merge changes made in one branch into another.

##### Gitlet Commands
- init
    - Creates a new Gitlet version-control system in the current directory. 
    - This will automatically start with one commit: a commit that contains no files and has the commit message “initial commit”
- add
    - Adds a copy of the file as it currently exists to the staging area
- commit
    - Saves a snapshot of tracked files in the current commit and staging area so they can be restored at a later time, creating a new commit
- rm
    - Unstage the file if it is currently staged for addition
- log
    - Starting at the current head commit, display information about each commit backwards along the commit tree until the initial commit, following the first parent commit links, ignoring any second parents found in merge commits. 
- global-log
    - Like log, except displays information about all commits ever made  
- find
    - Prints out the ids of all commits that have the given commit message, one per line. 
    - If there are multiple such commits, it prints the ids out on separate lines. 
- status
    - Displays what branches currently exist, and marks the current branch with a *
    - Also displays what files have been staged for addition or removal.
- checkout
    - Takes the version of the file as it exists in the head commit and puts it in the working directory, overwriting the version of the file that’s already there if there is one. The new version of the file is not staged.
- branch
    - Creates a new branch with the given name, and points it at the current head commit
- rm-branch
    - Deletes the branch with the given name
- reset
    - Checks out all the files tracked by the given commit. Removes tracked files that are not present in that commit. Also moves the current branch’s head to that commit node
- merge
    - Merges files from the given branch into the current branch
