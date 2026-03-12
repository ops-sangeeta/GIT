git init
- Initilises an git in a repo/folder
git status
- Gives summary of a that repo/ current status
git checkout -b <name>
- create a new branch inside the folder and switch to it.
git checkout <branch_name>
- to switch to other branch.
git add <name_file>
- add the file to stage location
git commit -m <"message">
- commit the file with the message from the staged location
git restore <file>
- restore the file from git if deleted from my local file system.
git restore --staged <file>
- it will untrack the staged file (if only add was executed)
git log
- gives the logs of commits made to git.
git revert <commit_id>
- will revert the commited deleted file 
git branch
- gives the info of all the branches
git clone <repo url>
- clone the file grom github to local or server
git push origin main
- publish my origin main to github origin main.
git pull origin main
- pull the files from github to local repo.
