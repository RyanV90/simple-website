Phonetic Alphabet Website

All information in this README taken from the following book:

Vormittag, R. (2016). A practical guide to Git and GitHub for Windows users:
From beginner to expert in easy step-by-step exercises. (n.p.). https://usermanual.wiki/Pdf/A20practical20guide20to20Git202620GitHub.1242881337. 

# tells git who you are
$ git config --global user.name "Your Name"

# tells git how to email you
$ git config --global user.email "your.email@domain.com"

# handles end-of-line character differences
$ git config --global core.autocrlf true

# prevents conversion warning messages
$ git config --global core.safecrlf false

# sets Notepad as the default editor
$ git config --global core.editor notepad

# list all current configuration settings
$ git config --list

# clone a GitHub repository
$ git clone <URL>

# check working directory changes
$ git status

# add changes to index
$ git add <folder>
$ git add <file>

# commit a new version
$ git commit -m <comment>

# identify remote repository
$ git remote
$ git remote show <repo name>

# push new version to GitHub
$ git push origin main

# show history of commits
$ git log --oneline --decorate

# list local branches
$ git branch

# list remote branches
$ git branch --remote

# view changes in the working tree
# not yet staged
$ git diff <file>

# view the changes between
# the index and the last commit
$ git diff --cached <file>

# view the changes in the working
# tree since the last commit
$ git diff HEAD <file>

# view changes between
# two commits
$ git diff <commit1> <commit2> <file>

# undo unstaged changes
$ git checkout <file>

# unstage changes
$ git reset HEAD <file>

# undo committed change
$ git revert <commit> --no-edit

# apply tag to a version
$ git tag -a <tag> <commit> -m <comment>


# move or rename a file
# and stage
$ git mv <source> <destination>

# delete a file and stage
$ git rm <file>

# create a branch
$ git branch <branch name>

# switch to another branch
$ git checkout <branch name>

# merge from branch
$ git merge <branch name>

# tag the last commit
$ git tag <version>

# add a new remote
# identified by upstream
$ git remote add upstream <URL>

# lists both local and
# remote tracking branches
$ git branch -a
$ git branch --all

# list remotes with URL
$ git remote -v
$ git remote --verbose

# fetch the latest commits from remote
# identified by upstream
$ git fetch upstream

# update local master from remote
# identified by upstream
$ git checkout master
$ git merge upstream/master

