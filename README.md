# git-demo

## first time
- step1 : created a repo on github account
- step2 : created a same name folder in local pc
- step3 : create any file in that folder for versioning
    - eg:  `echo "# git-demo" >> README.md`
- Step4 : initializing git in your local folder
    -  `git init`
- Step5 : to check the status of files (untracked files comes in red/ tracked files comes in green)
    - `git status`
- Step6 : to move file from untrack files to track files
    - `git add .` or `git add -A` -- to add all files to tracking
    - `git add <file-name>` -- to add specific file to tracking
    - `git add .csv` -- to add all csv files to tracking
    - let suppose you want to move files from tracking to untrack.
        - `git rm --cached <file-name>`
- Step7 : to make file ready to push we do commit.
    - `git commit -m "sending file to git"`
- Step8 : to make branch from master to main
    - `git branch -M main`
- Step9 : to set the origin for you local repo for github repo.    
    - `git remote add origin https://github.com/rashidsaleem755/git-demo.git`
- Step10 : to push files from local to github repo
    - `git push -u origin main`

## second time
- step1 : `git add README.md`
- Step2 : `git commit -m "second commit"`
- Step3 : `git push -u origin main`

## Branching
- step1 : to check on which branch you are
    - `git branch`
- step2 : to create and move to new branch
    - `git checkout -b task/development-branch`
    - if branch already exist -- `git checkout task/development-branch`

## upstreaming local and remote branch
- task/development-branch
	- branchibg code push
	
pull request to balance
	- main & task/development-branch
	- NOTE: pull request always balance git remote branches
	
- Now if we want to balance local 
	- git checkout main
	- git pull -- to take the code from git main branch