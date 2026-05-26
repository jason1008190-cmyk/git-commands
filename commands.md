# Git Commands Guide

This file explains essential Git commands and their associated flags.

## git clone
Creates a local copy of a remote repository.

## git checkout
Switches between branches or restores working tree files.

### -b
Creates a new branch and switches to it immediately.

## git status
Shows the state of the working directory and the staging area (which files are tracked, untracked, or modified).

## git push
Uploads local repository content to a remote repository.

### -u
Sets the upstream tracking reference for the branch you are pushing.

## git pull
Fetches changes from a remote repository and merges them into your current branch.

## git add
Adds file changes in your working directory to your staging area.

### -a
Automatically stages files that have been modified and deleted, but not new files.

## git commit
Records changes to the repository.

### -m
Allows you to write the commit message directly in the command line.

### -a
Automatically stages files that have been modified and deleted, but not new files, before committing.

### -am
A combination that stages modified files and adds a message in one command.

## git branch
Lists, creates, or deletes branches.

### -a
Lists all local and remote-tracking branches.

### -d
Deletes a specified branch (safely).

## git merge
Joins two or more development histories together.

## git init
Initializes a new Git repository.

## git log
Shows the commit history.

### --oneline
Shows a condensed version of the commit history.

## git diff
Shows differences between commits, commit and working tree, etc.

## git reset
Resets current HEAD to the specified state.

### --soft
Does not touch the index file or the working tree.

### --hard
Resets the index and working tree.

## git stash
Temporarily shelves changes you've made to your working copy.

### pop
Applies the most recently stashed changes and removes them from the stash.

## git remote
Manages set of tracked repositories.

### add
Adds a remote repository.

## git fetch
Downloads objects and refs from another repository.

## git rebase
Reapplies commits on top of another base tip.

## git tag
Creates, lists, deletes or verifies a tag object.

## git config
Gets and sets repository or global options.