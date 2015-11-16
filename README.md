# git_cheatsheet

List branches on machine:
$ git branch

Create and checkout branch
$ git checkout -b {newbranch}

List where all the branches have come from 
$ git remote show origin

Rename local branch$ git branch -m {newname}

Preview GIT committed changes: 
$ git log --graph --abbrev-commit --pretty=oneline --decorate

To see the difference between two branches in a readable format 
*Do exercise to fully understand*
 git diff --stat <branch1> <branch2>

To see which files have been created an which deleted
Git diff --summary <branch1> <branch2>

To show what is about to be pushed after committing
git diff --stat --cached origin/master

From <http://stackoverflow.com/questions/3636914/how-can-i-see-what-i-am-about-to-push-with-git> 
