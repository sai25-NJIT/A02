# A02
*Glossary is at the end of this file
In this readme file, I will be providing a step by step tutorial on how to set up Git, Github, and Webstorm. Firstly, Github is a platform for users to collaborate with each other on repositories of their choosing. Git is a source control management where a user can manage changes to files over time. Webstorm is an integrated development environment for coding in JavaScript. To get started with GitHub and Git, first install Git from https://git-scm.com/download if your machine doesn't already have it installed. GitHub utilizes Git as the actual version control system so they are used together. After installing Git, the next step is to create a GitHub account. Once done, connect your GitHub account to your Git account. In the Git terminal, type: git config --global user.name " ", where in the open quotes you type your username that you want. Next, you want to set your Git email by typing: git config --global user.email " ", where in the open quotes you type the email that you want. Then you will be asked to authenticate your GitHub account so just sing in with the same email to confirm. From here, you will be able to create and edit your code files locally. One of the main uses of GitHub is creating repositories, which are folders filled with code, and this can be done by clicking the + sign at the top right corner. The last main thing one should know about how to use Git and GitHub is that you can push your local code to GitHub. This can be done by using the code editor built-in terminal from Git. Input the commands that will be provided below after the other in the terminal and press the enter key after each command input. (NOTE: Capitalized words are for the user's personal input) 
- ‌echo "# sample-code" >> README.md
- git init
- git add .
- git commit -m "first commit"
- git branch -M main
- git remote add origin https://github.com/YOURUSERNAME/WHATEVERFOLDERYOUWANT
- git push -u origin main
  
There are many Git commands that a user is able to use in the terminal. Here I will provide common commands and a description of what they do.
- git init: intializes Git your folder
- git add Readme.md: adds a Readme file
- git add. : adds all files in the present folder
- git commit: stores the added files
- git branch: creates a new branch which is a new version of the repository as it appears when added
- git remote add origin: connects the local folder to the repository on GitHub
- git push -u origin main: pushes the code to GitHub

To use WebStorm, first download Webstorm from https://www.jetbrains.com/webstorm/. Afterwards, you can experiment with WebStorm and see its many features, but there are 4 main things that a user can do in WebStorm. The first thing a user can do is open a project. To do this, locate the Welcome Screen, click Open and then select the folder with your application in teh dialog that opens. Another thing a user can do is check out a project. First click Get from VCS on the Welcome Screen. When the dialog opens up, select the version control system from the list and specify the repository to check out the application sources from. To create an empty WebStorm project, clicke Create New Project on the Welcome screen or select File|New|Project from the main menu. A New Project dialog will open up and in the left-hand pane, choose Empty Project. In the right-hand pane, specify the application folder and click Create. Lastly, to create a new file in a project, select the folder where you want to create a new file and press Alt Insert in the Project tool window. The WebStorm interace if fairly easy to use. The WebStorm window consists of the Editor where you create, read, and modify code. It also consists of menus and toolbars, a navigation bar, a status bar, and a number of WebStorm tool windows. These secondary windows are attached to the bottom and to the sides of your workspace and they allow a user to debug code, run tests, and interact with the version control system. 

GLOSSARY
- branch: a pointer to a specific commit
- clone: primarily used to point to an existing repository and makes a clone or copy of that repository in a new directory or another location
- commit: a snapshot or milestone along the timeline of a Git project
- fetch: a primary command used to download contents from a remote repository
- GIT: a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency
- GitHub: a cloud-based Git repository that helps developers store, manage, track and control changes to their code
- merge: merging is Git's way of putting a forked history back together again. Allows a user to take the independent lines of development created by git branch and integrate them into a single branch
- merge conflict: an event that takes place when Git is unable to automatically resolve differences in code between two commits
- push: a command that is used to upload local repository content to a remore repository
- pull: a command used to fetch and download content from a remote repository and immediately update the local repository to match that content
- remote: a common repository that all team members use to exchange their changes
- repository: a central storage location for managing and tracking changes in files and directories 


Works Cited
Ajibola, Segun. “How to Use Git and GitHub – Introduction for Beginners.” freeCodeCamp, 26 September 2022, https://www.freecodecamp.org/news/introduction-to-git-and-github/. Accessed 30 September 2023.
WebStorm. “Getting started with WebStorm | WebStorm Documentation.” JetBrains, 6 September 2023, https://www.jetbrains.com/help/webstorm/getting-started-with-webstorm.html#ws_getting_started_go_to_declaration. Accessed 30 September 2023.
