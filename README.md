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

### Detailed explanation
`git init`
This command initializes a new Git repository in the current directory. It creates a new .git directory, which contains all the necessary files and folders for version control.

`git clone`
This command is used to create a local copy of a remote Git repository. It downloads all the files and folders from the remote repository to your local machine.

`git add`
This command adds files to the staging area, which prepares them for committing. It is used to tell Git which files should be included in the next commit.

`git commit`
This command creates a new commit, which is a snapshot of the changes made to the files in the staging area. It is used to save changes to the local repository.

`git push`
This command is used to upload the local repository to a remote Git repository. It sends all the new commits to the remote repository, making them available to other team members.

`git pull`
This command is used to download the latest changes from a remote Git repository. It fetches all the new commits from the remote repository and merges them into the local repository.

`git branch`
This command is used to create a new branch in the Git repository. It allows you to work on multiple features or bug fixes in parallel without affecting the main branch.

`git checkout`
This command is used to switch between different branches in the Git repository. It allows you to work on a specific branch and make changes without affecting other branches.

`git merge`
This command is used to merge two or more branches in the Git repository. It combines the changes made in different branches and creates a new commit with the merged changes.

`git log`
This command is used to view the commit history of the Git repository. It shows a list of all the commits made to the repository, along with the author, date, and commit message.
