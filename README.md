# git-commands
HEAD - currently active branch
remote - remote repo
origin - name of remote
main - first branch created

git clone <repo-name>
git status
git add .
git commit -m "commit message" 
git push
git pull

// testing merge conflicts

git branch <branch-name>
git branch (list of branches)
git switch <Branch-name>

// push branch to remote
git push -u origin <branch-name>

//delete branch from remote
git push -d origin <branch-name>


//stashing some changes
git stash
or
git stash save "name of stash"

//get stash
git stash pop

git stash -u -- stash untracked files too
git stash list

git stash pop stash-name

//restore stage changes
git restore --staged file-name
