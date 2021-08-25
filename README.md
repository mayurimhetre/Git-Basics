# Git-Basics

hi Mayuri


git config --system user.name "mayu"

git config --system user.email mhetremayuri@gmail.com

git config --help

git config --system --list --show-origin

git remote add origin "sitename"



######## moving file from local test folder to github repository


mkdir test
cd test

git config --system user.name mayurimhetre

git config --system user.email mhetremayuri@gmail.com

git status

git add test-demo-git-commands.txt

git commit -m "comit a file"

######### connenction to github username

git config --global user.username mayurimhetre

######### connection to git hub repository

git remote add origin https://github.com/mayurimhetre/Git-Basics.git

git push origin master

####### file will be present in github pull requests


################### branch changes #################

git branch

----> current branch is master

and now we are creating new branch "newbranch_name"

git branch newbranch_name

git chcekout newbranch_name

git rebase newbranch_name


################ .gitignore file

helps us to ignore files with extension mentioned in the format

*.log
*.class
*.pdf


################# FORK -- CLONE --- PUSH ---  PULL REQUEST

 fork ---> DEVELOPER1 git hub to DEVELOPER2 git hub 

DEVELOPER2 git hub ---> local machine D:/ folder

do changes in the file and push to DEVELOPER2 git hub

Now,raise a pull request and send it to DEVELOPER1 to approve it.




