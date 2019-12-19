# git commands

> Set your details to config (global)
`
git config –global user.name "[name]"
git config –global user.email "[email address]"
`

> Initialize a Git repository `git init`

> Create a local copy of a remote repository `git clone <https or ssh url>`

> Check status of your changes `git status`

> Add all new and changed files `git add -a, git add .`

> Add any specific file `git add <file name>`

> Commit changes `git commit -m "[commit message]"`

> Remove a file `git rm -r <file name>`

> Remove folder `git clean -fd`

> Push changes to remote repository `git push`

> Push changes to remote repository `git push -u origin <branch name>`

> Push a branch to your remote repository `git push origin <branch name>`

> Delete a remote branch `git push origin --delete <branch name>`

> Update local repository to the newest commit `git pull`

> Pull changes from remote repository `git pull origin <branch name>`

> List all local branches `git branch`

> List all branches (local and remote) `git branch -a`

> Create a new branch `git branch <branch name>`

> Delete a branch `git branch -d <branch name>`

> Delete a remote branch `git push origin --delete <branch name>`

> Create a new branch and switch to it `git checkout -b <branch name>`

> Clone a remote branch and switch to it `git checkout -b <branch name> origin/<branch name>`

> Rename a local branch `git branch -m <old branch name> <new branch name>`

> Switch to a branch `git checkout <branch name>`

> Switch to the branch last checked out `git checkout -`

> Discard changes to a file `git checkout <file name>`

> Merge a branch into the active branch `git merge <branch name>`

> Merge a branch into a target branch `git merge <source branch> <target branch>`

> Stash changes in a dirty working directory `git stash`

> Remove all stashed entries `git stash clear`

> Apply changes of your stash `git stash apply or git stash pop`

> Reset your added changes `git reset`

> Revert your all changes `git reset --hard`

> Go to your privious commit `git reset HEAD~ or git reset HEAD~<commit number>`

> Preview all changes `git diff`

> Preview changes for different branch `git diff <source branch> <target branch>`

> Add a remote repository `git remote add origin <https or ssh url>`
