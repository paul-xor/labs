##Git Useful commands:

$ git init

$ git status

##// add all changes to staging
$ git add .

##// commit changes
$ git commit -m “<comment what is done>”

##// pull all from remote repo
$ git pull

##BRANCH
##// create branch and switch to it
$ git checkout -b <name_of_branch>

##// list of branches 
$ git branch -v

##//switch between branches
git checkout master

// To push the current branch and set the remote as upstream, use
$ git push -u origin week_1_homework

MERGE
//need to switch to master first than
$ git merge week_1_homework

//push merged origin to remote repo
$ git push origin

//delete unnecesary
$ git branch -D week_1_homework

CONFLICT MERGE
$ git add .
$ git commit -m “fix merge conflict”
$ git push
