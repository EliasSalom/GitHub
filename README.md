# How to use Github and Git bash

**To download **
[Git Bash](https://gitforwindows.org/)

## First Time
>Go to the file directory

    1. git init 
    2. git add . or git add -A
    3. git commit -m "Comment"
    4. git remote add origin https://github.com/EliasSalom/rowad.git
    5. git push -u origin master

## Push and Pull
To Push all new code to GitHub

    git push origin master
to pull all the code from GitHub

    git pull origin master

##Branching
    git branch  //view all branch
    git branch elias1 //create a new branch
    git checkout elias1  //going to elias1 branch

## info
	git config --global user.email "elias.29@hotmail.com"
	git config --global user.name "elias salom"

## Error
    git push -f origin master
    git pull --rebase origin master
