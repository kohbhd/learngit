# Initiates an empty git repository
$ git init 

# Adds ALL the files in the local repository and stages them for commit OR if you want to add a specific file
$ git add . 

# To add a specific file
$ git add README.md 

# Lists all new or modified files to be committed
$ git status 

$ git commit -m "First commit"
# The message in the " " is given so that the other users can read the message and see what changes you made

$ git reset HEAD~1
# Remove the most recent commit
# Commit again!

git remote add origin https://github.com/kohbhd/learngit.git

git branch -M main

git push -u origin main