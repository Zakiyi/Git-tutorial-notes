# Git-tutorial-notes
This repository is created for learning basic Git operations using command line. The tutorial material include official Pro Git book as well as related youtube videos.

![](https://github.com/Zakiyi/Git-tutorial-notes/blob/master/git_index_structure.png)

## Initialization and Configuration 
```
git init      # Create a new git repository
git config --list   # check the config info
git config --global user.name    # set user name
git config --global user.email   # set user email
git config --global core.editor  # set default editor
git config --global alias.xx     # set alias of a command
```
## Basic Git Commands
```
git help <operation> or git <operation> -h    # get help of that operation 

git status      # checking the status of files, 
                  <options> -s: get simplified output
                        
git add         # takes a picture of what the files look like at current moment, and
                  add snapshot to staging area. more exactly, stores reference to that snapshot.

git commit      # records the snapshot you set up in your staging area, adds it to repository
                  <options> -a: stage every file that is already tracked before doing the commit
                       --amend: end up with a single commit — the second commit replaces the results of the first.
                        
git diff        # compares what is in working directory with what is in staging area.
git mv          # move file or rename file

git rm          # remove tracked file 
                  <options> -f: remove tracked file from staging area, and delete it from woking tree
                            -cached: remove tracked file from staging area but remain it in working tree
                                  
git log         # viewing the commit history
git reset       # unstaging a staged file
git checkout --   # unmodifying a modified file, restore a tracked file to the last snapshot
```

> It’s important to understand that git checkout -- <file> is a dangerous command.  Git just replaced that file with the most recently-committed version. &#x1F344; &#x1F344;
