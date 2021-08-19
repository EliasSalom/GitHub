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
```sh
git branch  //view all branch
git branch elias1 //create a new branch
git checkout elias1  //going to elias1 branch
git push -u origin <branch> \\push to new brunch
```
## info
```sh
git config --global user.email "elias.29@hotmail.com"
git config --global user.name "elias salom"
```
## Error
> wfsd
```sh
    git push -f origin main
```
> it's use to make pull and merge in the same time
```sh
    git pull --rebase origin main
```
> firce both branches to have the same history
```sh
git branch [branch 1] [branch 2] -f
```
