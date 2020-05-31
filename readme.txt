########
# useful commands 
########
git init
git status
git add .
git commit -m "message"



git log --oneline
git checkout <savepoint_id> ---> goto specific savepoint 
git revert <savepoint_id> --->remvoe specific savepoint
git reset <savepoint_id> --hard  ---> goto that commit and delete logs too


###
# Branch
###
git branch -a.  ----> show all branch
git branch DevJuned ---->create new branch 
git checkout master
git branch -D DevJuned ----> delete branch
git merge dev1
git merge dev2

