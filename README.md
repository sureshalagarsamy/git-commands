### Basic commands
* clear
* git status
* git add filename.js/css/html (stage specific file)
* git add --all / git add -A (stage all files)
* git checkout -- filename.js/css/html (Undo changes on particular file)
* git reset (unstage all files)
* git reset --hard (If you want to get a fresh copy equal to your HEAD branch)
* git commit -m "description"   /   git commit -m "description" --no-verify
* git pull origin branch_name (pull code from remote brach to local branch)
* git pull origin mater develop (pull code from remote branch 'master' to 'develop' branch)
* git push (It will push your commits to your remote branch)
* git branch -d PRU-123 (It will delete your local branch only. If there is a warning then use this git branch -D PRU-123)
* git checkout -b PRU-123 (It creates a new branch from your remote. So please make sure that you are in right remote branch like 'master / develop')

### Stash
* git stash save "my_stash"
* git stash list
* git stash apply stash@{n}    //Apply stash and keep the file(s) in stash itself
* git stash pop stash@{n}	//Apply stash and delete stash file(s) 

### Track Remote branch
* git branch --set-upstream-to=origin/develop <featurebranch>

### Rename remote branch
* git branch -m ABC-123 (ABC-123 is a new branch name.. Go to current branch and do this cmd)
