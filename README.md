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

//track remoet branch
git checkout --track origin/branch-name

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


GIT RESET
git reset --hard <commit-hash>

HEAD - 1 reset
git reset --soft HEAD~1

//testing reset
in the case of soft reset, file changes are maintained
only the commit history is changed
working directory and staging index are unchanged
so when we reset, all files are still changed, and staged but not committed.
like in vscode


//git tag
git tag tag_name

git push origin tag_name
