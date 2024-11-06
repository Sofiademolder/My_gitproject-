# Cheet sheet with commmands for Git

## Basic commands

- git init: initialize a new repository (only used the first time that you start a project locally)
When you start a project from GitHub, you don't need to do this
- git config --global --list: check whether the configuration is correct
- git config --global user.name "yourname": change the user name
- git config --global user.email "youremail: change the email address
- git add: adding any change in the staging area to monitor and keep track of it (do this first)
E.g.: git add file1 file2 file 3 
If you want to do git add for all the files you can do: git add *
- git commit -m "meaningful message": saving a point on the time line with a message that describes WHY, HOW, the EFFECT, and the LIMITATIONS of what you did  (do this next, after 'git add')


## More complex commands

- git mv old_file_name.txt new_file_name.txt: change the name of a file (still need to commit this)
- git status: git will tell you changes to be commited, changes not stages, and untracked files (file that has not been seen ever before by git, is not staged and not commited)
- git log: check the history of your time line to see all your changes (will be in reversed order) 
The first line is the unique identifier of each commit 
The second line is to see who commited
The third line is the time and date when this was commited
- git log -n 'number': limits the history 
git log --abbrev-commit: gives you a short- er ID that will still be unique 
- git diff HEAD <ID>: to travel in your timeline, to check differences between versions
- git diff <ID> HEAD: the order matters! now you see the opposite (things that have been added will look like they have been deleted)
- git show HEAD <ID>: will print all files with info per line for each file of what has been modified 

## Connect with GitHub

- You will need to create a repository on GitHub first
- git remote add <name> <ssh>: create bridge between local and remote
- git push -u master: this is what you do the first time you connect to push locally to the remote
- git push: now you will have pushed everything that has been commited from your local computer to GitHub
- git pull: when you or somebody else made a change on GitHub and you want to pull this change (= a commit) locally (e.g.: a new file)

Routine from loacl to remote:
```
git status
git add <file>
git commit -m "meaningful message"
git push

```