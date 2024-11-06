# Dictionary and concepts

- Git: Time line
- GitHub: Backup of the time line

## Conceptual Areas

1. Dev. area: the folder on the computer where the project is created
2. Staging area: where you prepare your snapshot that will go in my time line 
3. Local repository: your time line   
4. Remote repository: = a backup of the time line in GitHub

## Definitions

- Working tree area: this will tell you if you have any files left to be commited, staged or even tracked. You can check this by using 'git status'. if everything is okay, we will get a message saying: "nothing to commit, working tree clean"

- What happens if I forget the '-m' in the commit command? Git will force you to write a message! There is an advantage tho. In this way you will be able to write a longer message. Do 'i' (= insert) and write a longer message if you want this (text editor will open automatically)

- Why do you use a staging area? when you make unrelated changes to different documents, you don't want to commit them with the same message. By putting them one by one in the staging area, and then commiting a message, you can give them different meaningful messages. 