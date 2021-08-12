# How to use Github and Git bash

** To download **
[Git Bash](https://gitforwindows.org/)

## First Time
> Go to the file directory
```sh
    git init 
    git add .
    git commit -m "Comment"
    git branch -M main
    git remote add origin <repostory>
    git push -u origin main
```
## Push and Pull
To Push all new code to GitHub
```sh
    git push 
```
> OR this code in case have another prunch
```sh
git push origin main
```
> OR push an existing repository from the command line
```sh
git remote add origin https://github.com/EliasSalom/{repository}
git branch -M main
git push -u origin main
```
> To pull all the code from GitHub
```sh
    git pull
```

## Branching

    git branch  //view all branch
    git branch elias1 //create a new branch
    git checkout elias1  //going to elias1 branch
    git push -u origin <branch> \\push to new brunch

## info
	git config --global user.email "elias.29@hotmail.com"
	git config --global user.name "elias salom"

## Error
    git push -f origin master
    git pull --rebase origin master
