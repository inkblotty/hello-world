hello, world!

It's a beautiful day to learn Git.

Notes on Git
============
Create a new Git-connected Repository:
--------------------------------------
$ mkdir <FOLDERNAME> = creates new folder/repository
$ cd <FOLDERNAME> = goes into that folder
$ git init = turns Git on for that folder
$ ls = lists the items in that folder

Add files and check status of files in repository:
--------------------------------------------------
$ git status = checks items in that repository
$ git diff = views changes to files
$ git add . = adds all changes for commit
$ git add <FILENAME> = adds a created file's changes to be committed
$ git commit -m "<your commit message>"

Remote connection:
------------------
$ git remote add <REMOTENAME> <URL> = adds remote connection; usually REMOTENAME is "origin" or "upstream", etc.
$ git remote -v = view remote connections

Push and pull files to/from GitHub:
-----------------------------------
** these changes after remote connection established and new repository with identical name is created on GitHub **
$ git remove pull <REMOTENAME> <BRANCHNAME> = pulls changes from GitHub
$ git remote -v = views remote connections
$ git push <REMOTENAME> <BRANCHNAME> = pushes changes to GitHub (git push -u origin master, in this case)
$ git clone <FORKEDURL> = clones a forked project from GitHub to local machine

GitHub Pages:
-------------
** GitHub automatically serves and hosts static website pages in branches marked "gh-pages". These sites are at:
http://githubusername.github.io/repositoryname

Branches:
---------
$ git checkout -b <BRANCHNAME> = creates and switches to a branch in one line
$ git branch <BRANCHNAME> = creates a new branch
$ git checkout <BRANCHNAME> = moves into the branch
$ git branch = lists the branches
$ git branch -m <NEWBRANCHNAME> = rename the current branch
$ git status = verifies which branch you're in
$ git pull <REMOTENAME> <BRANCHNAME> = pulls in changes from a remote branch (maybe added by other contributor)
$ git fetch --dry-run = see changes to remote branch before pulling them in

