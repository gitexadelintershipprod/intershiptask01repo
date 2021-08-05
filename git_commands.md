git config --global user.name "gitexadelintershipprod"
git config --global user.email "gitexadelprod@gmail.com"
git config --global user.password "********"
git config --global --list
cd /c/users/admin/Documents/task01/
git init
mkdir Task1
touch README.md
git add README.md
git commit -m "Master Branch First Commit"
git remote add origin https://github.com/gitexadelintershipprod/intershiptask01repo.git
git commit -m "Master Branch second Commit"
git push -u origin master

cd /c/users/admin/Documents/task01/

git branch dev
git checkout dev
touch TEST.md
git add TEST.md
git commit -m "dev Branch First Commit"
git push -u origin dev

git branch gitexadelintershipprod-new_feature
git checkout gitexadelintershipprod-new_feature
touch README.md
git add README.md
git status
touch .gitignore
git add .gitignore
vim .gitignore

Insert text : 
# ignore files start with
"."

cat .gitignore
git add .gitignore
git commit -m "gitexadelintershipprod-new_feature Branch First Commit"
git push -u origin gitexadelintershipprod-new_feature
git checkout dev
git pull origin dev
git merge gitexadelintershipprod-new_feature

git pull origin master
git checkout master
git merge dev

git checkout gitexadelintershipprod-new_feature
touch README.md
git add README.md
vim README.md

Insert text : 
# test change

git add README.md
git commit -m "gitexadelintershipprod-new_feature Branch Second Commit"
git log --oneline gitexadelintershipprod-new_feature
git revert "aad3801"

git checkout master
git branch -a
git branch -D gitexadelintershipprod-new_feature
git push origin --delete gitexadelintershipprod-new_feature
git branch -a
git commit -m "Master Branch 03 Commit"
git push -u origin Master


git log > log.txt

git checkout dev
touch git_commands.md
git add git_commands.md
vim git_commands.md
git commit -m "dev Branch Second Commit"
git push -u origin dev
