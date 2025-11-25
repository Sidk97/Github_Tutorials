# Github Tutorials




## Overview
- Creating a Github repository
- Installation of Git Cli (Command Line Interface)
- Configuration


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
## Pushin files on to Repository
_Concept_:- Before any file is pushed on to the repository, the files are first added/staged on to a staging environment.

In order to check modified files and untracked files inside the workspace, 
```
git status
```
This gives an overview of the status of the files whether these have been modified or untracked files

``
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
