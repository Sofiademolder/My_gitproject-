# Cheet sheet with commmands for Git

## Basic commands

- git init: initialize a new repository (only used the first time that you start a project locally)
When you start a project from GitHub, you don't need to do this
- git config --global --list: check whether the configuration is correct
- git config --global user.name "yourname": change the user name
- git config --global user.email "youremail: change the email address
- git add: adding ant change in the staging area to monitor and keep track of it (do this first)
E.g.: git add file1 file2 file 3 
If you want to do git add for all the files you can do: git add *
- git commit -m "meaningful message": saving a point on the time line with a message that describes WHY, HOW, the EFFECT, and the LIMITATIONS of what you did  (do this next, after 'git add')
- git log: check the time line of your changes 

## More complex commands

- git mv old_file_name.txt new_file_name.txt: change the name of a file (still need to commit this)
- git status: git will tell you changes to be commited, changes not stages, and untracked files (file that has not been seen ever before by git, is not staged and not commited)
