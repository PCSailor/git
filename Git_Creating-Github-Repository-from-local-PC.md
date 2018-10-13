# Creating a Github repository from a local computer
## Basic workflow
* git add
* git commit "text"
* git push
## In terminal:
*	Open cmd.exe or preferred terminal
*	Navigate into, or create, the folder needed to be uploaded to Github
*	Verify files and sub-folders are ready to upload
*	git init
## On the internet:
*	Within a profile on www.github.com, create a repository for these local computer files & folders
*	In that new repository, go to ‘Clone or Download’ and copy the ‘web URL’ (for example: <https://github.com/PCSailor/git.git>)
## In terminal:
*	git remote add origin https://github.com/PCSailor/git.git
*	git add .
*	git commit -m "initial commit"
*	git status
*	git push  origin master 
*	git push –u origin master
    + for first push
*	git push –f origin master
    + for force overwrite
## Set Global Configuration:
*	git config --global user.name "name"
*	git config --global user.email "email"
*	cat ~/.gitconfig
    + check status

https://python-forum.io/Thread-Basic-Creating-a-repo-for-your-completed-scripts

