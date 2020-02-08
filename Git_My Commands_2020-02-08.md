Git_My Commands.md
# My Github profile: <https://github.com/PCSailor

| Command: | Description: |
| -------- | ------------ |
| cd | navigate to ... |
| ls | list directory contents |
| ls -a | show hidden files & folders |
| dir | list directory contents |
| mkdir | create directory |
| touch | create file |
| rm-rf <dirName> | Removes directory & all contents |
| rm <fileName> | Removes file (can enter multiple files seperated by space) |
| ... rm origin | origin replaces www address |
| git log | shows activity log |
| git pull origin master | pulls remote changes in Github repository |
| git diff HEAD | inspect commit differences |
| git diff <add path &/or file> |  |
| git diff --staged | see the staged changes |
| git reset | removes staged files |
| git checkout -- <target> | files changed back to last commit |
| git branch <createName> | creates a branch to edit independent from master branch |
| git checkout <any branch name> | switch branches |
| git remote -v | shows current github repository |
| Github Terminal Login: |
|   git config --global user.name "Philip Curtis" (sameAs git config --g) |
|   git config --global user.email "phil@philcurtis.io" |
| code . | opens in VSC |
| atom . | opens in Atom |
| VIM: |
|   :q ! | Quit/Exit VIM |
|   Alternative text editor commit: | i, ESC, add message, :wq (or :qw) |
| -a | added to a command, adds all files & folders |
| https://try.github.io | Excellent tutorial |


# Basic flow:
git add .
git commit
git push

# Workflow on existing Github repositories:
Navigate to directory
git init # creates hidden directory for Github.com
git status # check git init success with red files
git add . # adds new/modified files, without deleted, for inclusion in next git commit
  git add -A stages all
  git add -u stages modified & deleted, without new
git status # check git add success with green files
git commit -m "message"
git remote add origin <add github-repositiory www>
git push -u origin master
  -u only for 1st push, -f to force
  :q quits VIM

# Create new repository from command line
Navigate to directory
git init
git add .
git commit -m "message"
git remote add origin <add github website>
git push -u origin master

# Push existing repository from command line
git remote add origin <add github website>
git push -u origin master

# Join repository as collaborator
git clone <add github address>
Navigate to directory & edit code as needed
git add .
git commit -m "message"
git push

# Update local files with newer repository
git checkout <branch name>
git branch
git pull
git checkout . # deletes changes to files