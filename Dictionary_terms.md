# Dictionary and concepts

- Git: Time line
- GitHub: Backup of the time line

You need to review and accept my amazing suggestion!



## Conceptual Areas

1. Dev. area: the folder on the computer where the project is created
2. Staging area: where you prepare your snapshot that will go in my time line 
3. Local repository: your time line   
4. Remote repository: = a backup of the time line in GitHub

## Definitions

- Working tree area: this will tell you if you have any files left to be commited, staged or even tracked. You can check this by using 'git status'. if everything is okay, we will get a message saying: "nothing to commit, working tree clean"

- What happens if I forget the '-m' in the commit command? Git will force you to write a message! There is an advantage tho. In this way you will be able to write a longer message. Do 'i' (= insert) and write a longer message if you want this (text editor will open automatically)

- Why do you use a staging area? when you make unrelated changes to different documents, you don't want to commit them with the same message. By putting them one by one in the staging area, and then commiting a message, you can give them different meaningful messages. 

- Detached head: 

## Solving issues

- How can I go back to the old version of my file if I accidentally changed something? 
git revert <ID>: you find the <ID> by using git log of the document you want to revert (get rid of this one)

- How can I recover my local repository if I deleted it completely? 
git clone <SSH>: this will not restore the files from the .ignore file!  
git clone <HTTPS>: if you don't own the repository (SSH will not work) 

- What is the difference between git clone and git pull? 
Git pull will add all the new commits made and put them locally (it will not make a cross-reference)
Git clone takes everything from the repository and puts it locally

## Collaborating on GitHub

Push and pull are very important to avoid conflicts! 

Go to settings on GitHub and select collaborators (login with the Authenticator on your phone)
You can add people by username of by email 
This person then needs to accept the collaboration

## Solving conflicts 

see presentation

## Branching and the use of it

- Alternative history
- Specific names
- Independent timelines
- Connected to a moment in time

## Merging

- git merge <branch_name>: 
when you want to merch branches back together
Very likely to run into a conflict here! But minimize the number of conflicts and name one person to be responsible for solving them 

## Branching

Creating parallel timelines

### The mirror effect

When creating a parallel timeline, the folder in your computer becomes a portal that shows only the reality you choose to be.

when doing `git check <branch>` you choose which reality you are updating, therefore the one you see in your folder.


Helloooo
I hope you are enjoying!!
You are welcome to get in touch later if you have extra questions or challange.
I'll be happy to help!

cheers


## Working in an alternative universe: branching

Creating a branch:
- Alternative history of commits
- Specific names
- Independent timelines
- Connected to a moment in time 

Use of a branch:
- Experiment risk free
- Collaborate in a project: you can work at the same time if you both use your own branch 
- Use different versions of a software

## Tagging

Tagging is used to give a name to your commits. I don't understand why you would need this. I think it is useful if you want to releases diferent versions of your work, and this then allows you to give your work specific names. People can then download the versions (names by the tag), which will be a zip file. 

## Forking

Makes a complete copy of the current state of a master branch. You will now earn this 'fork' of the project in this state. 

## Working remoteley

Go to your project in GitHub and press '.'
You will not be able to stage, and everything you commit is immediately pushed 
(There is no terminal)
You need to commit and push by clicking on the branch symbol on the right