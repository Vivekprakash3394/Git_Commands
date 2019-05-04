### Getting & Creating Projects

| Command 														   | Description                                   |
| ---------------------------------------------------------------- | --------------------------------------------- |
| `git init`                                                       | ==>Initialize a local Git repository
| `git clone https://github.com/[username]/[repository-name].git`  | ==> Create a local copy of a remote repository
| `git clone https://github.com/Vivekprakash3394/Git_Commands.git` | ==>Example of git clone 




### Add one or more files to remote repository

| Command      | Description                      |
| ------------ | -------------------------------- |
| `git status` | ==> Check status 
| `git add`    | ==> Add a file
| `git add -A` | ==> Add all new and changed files




### Commit changes to head (but not yet to the remote repository)

| Command                            | Description |
| ---------------------------------- | --------------------------- |
| `git commit -m "[commit message]"` |==> Commit changes 
| `git rm -r [file-name.txt]`        |==> Remove a file (or folder)




### Send changes to the master branch of your remote repository

| Command                                  | Description                                                  |
| ---------------------------------------- | ------------------------------------------------------------ |
| `git push origin [branch name]`          |==> Push a branch to your remote repository
| `git push -u origin [branch name]`       |==> Push changes to remote repository (and remember the branch)
| `git push`                               |==> Push changes to remote repository (remembered branch)
| `git push origin --delete [branch name]` |==> Delete a remote branch




### Fetch and merge changes on the remote server to your working directory

| Command                                                                         | Description                                    |
| ------------------------------------------------------------------------------- | ---------------------------------------------- |
| `git pull`                                                                      |==> Update local repository to the newest commit
| `git pull origin [branch name]`                                                 |==> Pull changes from remote repository
| `git remote add origin https://github.com/[username]/[repository-name].git`     |==> Add a remote repository
| `git remote set-url origin https://github.com/[username]/[repository-name].git` |==> Set a repository's origin branch
| `git merge [branch name]`                                                       |==> Merge a branch into the active branch 
| `git merge [source branch] [target branch]`                                     |==> Merge a branch into a target branch 
| `git fetch origin`															  |==> Download objects and refs from another repository



### Branching

| Command                                              | Description                                              |
| ---------------------------------------------------- | -------------------------------------------------------- |
| `git branch`                                         |==> List branches (the asterisk denotes the current branch)
| `git branch -a`                                      |==> List all branches (local and remote)
| `git branch [branch name]`                           |==> Create a new branch 
| `git branch -d [branch name]`                        |==> Delete a branch 
| `git checkout -b [branch name]`                      |==> Create a new branch and switch to it
| `git checkout -b [branch name] origin/[branch name]` |==> Clone a remote branch and switch to it
| `git checkout [branch name]`                         |==> Switch to a branch
| `git checkout -`                                     |==> Switch to the branch last checked out
| `git checkout -- [file-name.txt]`                    |==> Discard changes to a file
| `git stash`                                          |==> Stash changes in a dirty working directory
| `git stash clear`                                    |==> Remove all stashed entries
| `git diff [source branch] [target branch]`		   |==> Preview changes before merging 



### Inspection & Comparison

| Command 									 | Description                      |
| ------------------------------------------ | -------------------------------- |
| `git log`                                  |==> View changes
| `git log --summary`                        |==> View changes (detailed)
