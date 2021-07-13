

## ADF

* **Assignment: 1.6 Version Control & Workflow**
* **Name: Kai Snyder**
* **Date: July 5th, 2021**
* **Due: July 12th, 2021**

## Topic: Terminal
Professional developers use Terminal daily. It's essential to understand some fundamental commands to use the application.   

**1. Using Terminal, there are essential commands to know.**

List the correct Terminal commands to do the actions listed below. Replace **CMD** with the correct command sequence. You can keep or enhance the brief description. 

**The last bullet provides an example**.

* [ CTRL + L ]: Clear the Screen 
* [ pwd ]: Print the "Working Directory"
* [ ls ]: List files and folders
* [ la -a ]: List files and folders, including invisible files
* [ ls -lh ]: List all files and folders, in human readable form
* [ cd ]: Change directory
* [ cd / ]: Change directory, go to root directory
* [ cd ~ ]: Change directory and go to user home directory
* [ cd .. ]: Change directory, go up one folder level
* [ cd ../.. ]: Change directory, go up two folder levels
* **cd ~/Desktop/**: Change directory to my desktop! 


**2. Using Terminal...**

**Folder Drop:** Try typing "cd" followed by a space, and then drag a folder into terminal and press return. Test this out and describe your results below.  

[ I dragged my screenshot folder into the termal(the folder I keep all of my school screenshots on my mac) and the working directory changed to that folder instead of the main one. So it printed out "/Users/kaisnyder/Desktop/schoolss" instead of just "/Users/kaisnyder" .]


## Topic: Version Control & Git
Version control, also known as revision control, records changes to a file or set of files over time so that you can recall specific versions later. In this class, we are learning Git. Update the information below where indicated.  

**1. There are three types of version control.**

[ Local, Centralized, Distributed ]



**2. Using Terminal, there are also essential Git commands to know.**

List the correct Git commands to do the actions listed below in Terminal. Replace CMD with the correct command and keep or enhance the brief description. **The last bullet provides an example**. 

* [ git clone [url] ]: Clone a repository
* [ git config --global user.name]: Set-up a global user name
* [ git config --global user.email ]: Set-up a global email address (to match my GitHub account eMail)
* git status : [ show modified files in working directory, staged for your next commit ]
* [ git add ]: Add modified files to the next commit
* [ git commit ]: Make a commit with a new message
* [ git log ]: Show my commit history
* **git help**: This command will bring up Git's help screen in Terminal!
    



**3. Connecting to GitHub using Terminal.**
HTTPS is the the correct way to connect to GitHub in this course. Describe how you connect to GitHub from Terminal using this protocol. What steps do you take? 

[ Create a new repository on GitHub, Open terminal, change ld to local project, Initialize ld as Git repos, Add files to new local repos, Commit files that are staged to local repos, Copy repos URL with HTTPS, In terminal add URL where it will be pushed, Push changes to repos in GitHub. ]



**4. Using .gitignore and Why it's Important**  
Most repositories contain a .gitignore file. 

* What is the purpose of this file?  
* What is the "**.DS_Store**" file and why would you want to ignore it?
* What other file or folder would you want to add to a .gitignore file and why? 


[ 
*So certain files not tracked by git, remain untracked. 
*These files contain information about system configuration. They can grab information about your computer.
*OS fIles, Lang files, App files, so no private information on your computer can be seen. ]



<br>

# Reference Links
Replace the example references below with your own links and recommended resources. It is acceptable to provide multiple links for a single topic and to use material provided to you in this class. You are encouraged to link to your own independent research as well. 

[ Research Summary: What resource(s) did you find most helpful this past week and why? ]

**Terminal Commands**  
[Learn Python The Hard Way](https://learnpythonthehardway.org/book/appendixa.html)  

**Three Types of Version Control**  
[Serengeti](https://serengetitech.com/tech/introduction-to-git-and-types-of-version-control-systems/)

**Git Commands**  
[GIT](https://git-scm.com/)

**Connecting to GitHub using Terminal**  
[GitHub Docs](https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github/adding-an-existing-project-to-github-using-the-command-line)

**Using .gitignore and Why it's Important**  
[Zell](https://zellwk.com/blog/gitignore/)




