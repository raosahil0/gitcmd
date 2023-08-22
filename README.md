# gitcmd
I have installed Git on Windows. I am uploading my project by creating a new repository, but it did not upload by command line.
Step-1:
Download git from here
Step-2:
Create a repository in github
Step-3:
goto your project folder
step-4
open git bash or cmd and initialize your project by typing git init
step-5
add files by typing git add . for adding all file
step-6
commit your project by typing git commit -m 'your message'
step-7
copy your remote location from github by typing
git remote add origin 'your repository link'
step-8
push your code in github by typing git push -u origin master
and thats all you need to do. Or check github documentation.


How do I upload a project on GitHub?
1.	Create a repository in GitHub
2.	Open Git Bash
3.	Select the repository directory (cd <path to folder>)
4.	Run the following commands.
           git init
           git remote add origin <repository clone link>
           git add .
           git commit -m "commit"
           git push origin master

5.	Reload your GitHub repository page …
6.	Now your project will upload successfully
