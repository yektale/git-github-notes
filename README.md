# Header

In this file i will list the commands in git i have learned while studying git

## Command line prompts

`mkdir <...>`       create new dir

`cd <...>`          go to said dir

`touch <...>`       create new file

`ls`          list all files in dir

`ls -a`       list all files + hidden ones in dir

`ls -l`       list all files in dir with detail

`ls -la`      the last two together

#### `ls -la` command equivalents for Powershell

```
Get-ChildItem -Force

ls -Force
```

## Git commands

`git version`     checks git version, good for checking if git is present

`git clone <...>`       clones a repository

`git init`        initalizes git, creating a .git folder in dir

`git status`      shows what changes have been made in dir

`git add <...>`        adds files and folders to stage

- `git add --all`      adds all files in project
- `git add -A`         same as above
- `git add .`          adds all files inside dir (best practice is to use this on root file to add all files)
- `git add *`          adds all files, but will miss files that are deleted (also some other details, maybe dont use this one)

`git reset`         removes everything from stage

`git commit -m ""`        makes all changes added into stage to the local repo, part in quotes is for the commit message

`git config --global user.email ""`     necessary for git to know to make commits, local

`git config --global user.name ""`      same as above but only a name

`git reset HEAD~`

`git rm`          deletes file and adds the deletion to stage

- `git rm --cached`

