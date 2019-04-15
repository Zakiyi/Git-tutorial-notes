# Git-tutorial-notes
This repository is created for learning basic Git operations using command line. The tutorial material include official Pro Git book as well as related youtube videos.

## Initialization and Configuration 
```
git init      # Create a new git repository
git config --list   # check the config info
git config --global user.name    # set user name
git config --global user.email   # set user email
git config --global core.editor  # set default editor
git config --global alias.xx     # set alias of a command
```
## Basic git operations
```
git help <operation> or git <operation> -h    # get help of that operation 
git status            # checking the status of files, 
                        <options> -s get simplified output
git add               # take snapshots of the revised files, and add snapshots to staging area
git commit            # records the snapshot you set up in your staging area, adds it to repository
                        <options> -a stage every file that is already tracked before doing the commit
git diff              # compares what is in working directory with what is in staging area. 
```
