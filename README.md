git cherry-pick is almost same as git merge except it only merges at a specific commit, not subsequent commit. For example, commit a, commit b. If you want commit a, cherry-pick --edit a.
git cherry-pick --edit <hash>  // stay on your current branch to merge files into your current branch from another branch.
Solve merge conflict
git add .
git commit -m 
git push

git cherry-pick -n <hash>  // you can work on current branch after commit
solve merge conflict
git add .
git commit -m
git push



