Changed the first line on a new branch. 

Git

we can keep track of all changes

for new repository:

git init
git add file.name
git commit -m "first commit”

git remote add origin git@github.com:RonShalevich/a.git
git push -u origin master

git status
to see what is the status

git log
to see history of commits

git add . (all files)
git add -A (all files including deletion)
git fie (to add specific file)

git diff ( to see the changes)

git status to see the modified file

git add
git commit

git add -p (interactive addition by line)

git reset file.name (to undo all the staging)

git diff —staged (to see the staged lines)

git log -p (to see changes and diff on every commit)

create another branch:
git branch field-trip

to change branches
git checkout field-trip

git pull (download and update in one step)
git fetch (download but doesn't update automatically)
git merge origin/master (to update after fetch)

git log —graph —oneline (to see changes in agit  oneliner)
to delete a branch
git branch -D branch
then need to delete on github

added a line
