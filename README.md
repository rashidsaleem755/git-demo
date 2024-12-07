# git-demo

step1 : created a repo on github account
step2 : created a same name folder in local pc
step3 : create any file in that folder for versioning
    - eg:  `echo "# git-demo" >> README.md`
Step4 : initializing git in your local folder
    -  `git init`
Step5 : to check the status of files (untracked files comes in red/ tracked files comes in green)
    - `git status`
Step6 : to move file from untrack files to track files
    - `git add .` or `git add -A--` to add all files to tracking
    - `git add <file-name>` -- to add specific file to tracking
    - `git add .csv` -- to add all csv files to tracking
    - let suppose you want to move files from tracking to untrack.
        - `git rm --cached <file-name>`
Step7 : to make file ready to push we do commit.
    - `git commit -m "sending file to git"`
Step8 : to make branch from master to main
    - `git branch -M main`
Step9 : to set the origin for you local repo for github repo.    
    - `git remote add origin https://github.com/rashidsaleem755/git-demo.git`
Step10 : to push files from local to github repo
    - `git push -u origin main`