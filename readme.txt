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

Push and pull files to/from GitHub:
-----------------------------------
** these changes after remote connection established and new repository with identical name is created on GitHub **
$ git remove pull <REMOTENAME> <BRANCHNAME> = pulls changes from GitHub
$ git remote -v = views remote connections
$ git push <REMOTENAME> <BRANCHNAME> = pushes changes to GitHub

