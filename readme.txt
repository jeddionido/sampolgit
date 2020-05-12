GIT
Version Control System
system that record changes
to a file
2 main feature
manage version
Create a snapshot of the project folder
saves the author and date and time
switch back to previous version
make coworking easier
push all your work to remote server
pull someone's work

How to manage versions
install git
initalize git project
start tracking files
modify files
take a snapshot

state of files
untracked git is not watching (git add is not yet run)
staged file is marked to be included in next commit
unstaged - file wont be included in next commit
commited - file snapshot was made


Git Branching - "killer feature"
Branch - lightweight movable pointer
to on of commits. On every commit, branch pointer
moves forward automatically.
it creates a master bridge.

merge


when commiting you need to specify
git init
git status
git add - (git add . (take every file which is not tracked yet to move to staged area always git status)
git commit - (git commit -a include unstaged stages) (git commit -m message)
git .config --global user.email ""
git config --global user.name ""

to add remote repo
git remote add orgin ""
git remote -v
git fetch (fetch to take from the remote)
git push to the repo
git push origin master (bridge)
git push origin --delete ""
git clone ""

git checkout -b (creates new branch)
git checkout (to switch branches)
git diff (to see what is modified)
git merge "" (to merge in master branch, checkout first)



:wq











