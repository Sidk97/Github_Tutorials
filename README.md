# Github Tutorials
The objective of this repository is to document my learning about Git and its commands.



## Overview
- Creating a Github repository
- Installation of Git Cli (Command Line Interface)
- Configuration
- Pushing Files to the Repository

## Installation

Install git cli for the operating system that you are using from the official website https://git-scm.com/install/windows

Once Installed the installation can be verified using the command prompt

```sh
git --version
```

## Setup
Open the workspace folder 
```
git init
```
What this does is that it creates a _.git_ folder which signifies that the workspace is initialized with Git.

### Configuration
For the intial use of the repository, the user name and the email id needs to be configured. For in detail information refer to https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration#:~:text=needs%20it%20to.-,Git%20Configuration,-As%20you%20read

Inside the project folder 
```sh
git config --gloabl user.name"Your_name"
git config --global user.email your_email_id
```
## Pushing files on to Repository
_Concept_:- 
1.Before any file is pushed on to the repository, the files are first added/staged on to a staging environment.
2.There are three steps before the files are pushed to the repository,
a. **Add** the desired files to the staging environment.
b. **Commit** the file to the staging environment.
c. **Push** the file to the repository hosted on GitHub or GitLab.

In order to check modified files and untracked files inside the workspace, 
```
git status
```
This gives an overview of the status of the files whether these have been modified or untracked files

```
git add <file_name>
```
This adds the desired file to the staging area so that it can then be further pushed to the repository.

```
git add .
```
This adds all the files to the staging area so that it can then be further pushed to the repository.

```
git commit -m "First Commit"
```
This will make sure that it goes to the staging environment with the desired message

```
git branch
```
To check the branch on Github

```
git branch -M main
```
To rename the branch from "Master" to "main".

```
git remote add origin https://github.com/Sidk97/Github_Tutorials.git
```
This links the local repository to the Github repository where the files need to be pushed to._origin_ is the variable/name assigned to the repository.


```
git push origin main
```
This pushes the code/files to the repository.

##  Restoring Files

In order to unstage a file from the staging environment 
```
git restore --staged "file_name"
```
OR
```
git reset file_name
```

In order to view the what is changed but not staged
```
git diff
```

In order to view what is staged but not yet commited 
```
git diff --staged
```
## Branching and Merging
Lets stay you want to create and work on a copy of the main branch, to do this we create another branch.
Basically,  Branching in Git allows you to diverge from the main line of development and continue to work independently without affecting the main line.

```
git branch <branch_name>
```
Lets consider _developer_ as the new branch name

To make this as the primary branch for commiting changes
```
git checkout developer
```
### Merging - Timestamp 10:09

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
