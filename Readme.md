#This is a very first github file
#Basic github command to remember

git init
git add hello.py
git commit -m "add hello.py"

#by default git points to master (main) branch
#run git log then check HEAD-> current branch
git log
#create a new branch: git branch [branch-name]
git branch branch-name
#switch and on new branch
git switch branch-name
#check by running git log command again
git switch -c branch-name
#create and switch branch at same time.
