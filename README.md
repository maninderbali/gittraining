
# gittraining
git config
git clone
git fetch
git pull
git checkout
git push
git merge
git rebase
git reset
git stash


Tell Git who you are:

git config --global user.name "maninderbali"
git config --global user.email "maninder.bali@sorpasteria.com"

Create a new local repository: git init

Create a working copy of a local repository: git clone /path/to/repository

Add files: git add <filename>, git add *

Commit changes : git commit -m "Commit message"

Commit any files you've added with git add, and also commit any files you've changed since then: git commit -a

Send changes to the master branch of your remote repository: git push origin master

List the files you've changed and those you still need to add or commit: git status

Create a new branch and switch to it : git checkout -b <branchname>

Switch from one branch to another:  git checkout <branchname>

List all the branches in your repo, and also tell you what branch you're currently in: git branch

Delete the feature branch: git branch -d <branchname>

Push the branch to your remote repository, so others can use it: git push origin <branchname>

Fetch and merge changes on the remote server to your working directory: git pull

To merge a different branch into your active branch: git merge <branchname>

View all the merge conflicts: git diff

View the conflicts against the base file: git diff --base <filename>

Preview changes, before merging: git diff <sourcebranch> <targetbranch>

After you have manually resolved any conflicts, you mark the changed file: git add <filename>

To view the log : git log

If you mess up, you can replace the changes in your working tree with the last content in head: git checkout -- <filename>

Instead, to drop all your local changes and commits, fetch the latest history from the server and point your local master branch at it, do this: git fetch origin; git reset --hard origin/master
