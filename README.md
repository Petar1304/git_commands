git init
git add filename
git add .
git reset (undo whole add)
git rm --cached (removes added file)
git status
git commit -m "Commit"

# branches
git checkout -b new_branch
git checkout master (change branch to master)
git branch -M new_name (renames branch)
git branch -d branch_name (delete branch)
git branch (list all branches)
git merge new_branch (merge master with new_branch)
# if we have conflicts go to file and edit it

# shortcut to add everything and commit
git commit -am "Message"

git remote add origin https://github.com... (add remote repository(origin))
git remote (list remote repositories)
git push -u origin main
git pull (pull changes from remote repository)
git clone

for github:
git remote add origin https://github.com/Petar1304/test.git
git push -u origin master ( -u => save settings)
