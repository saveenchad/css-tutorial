### Things to fix

# css-tutorial
Examples of css styles according to the CSS3 spec

# How to Git

### Pull the remote repo

(ssh) `git clone git@github.com:saveenchad/css-tutorial.git`

(https) `git clone https://github.com/saveenchad/css-tutorial.git`

### Make a local dev branch to work on

`git checkout -b dev`

### When you want to commit

`git status` to see which files you have edited

`git add .` to stage the files of the current directory

`git commit -m "INSERT COMMIT MESSAGE HERE"` to commit the staged files

`git checkout master` to go back to master branch that everyone has access to

`git pull origin master` to pull the latest code onto master branch

`git rebase master dev` to put what you just pulled onto your dev branch. Moves you automatically to dev branch. You might get merge conflicts here so just follow the instructions on the console to fix

`git checkout master` to get back to master after rebasing

`git merge master dev` to merge your commits onto master

`git push origin master` to push code to remote repo

`git checkout dev` move back to dev branch to do more work
