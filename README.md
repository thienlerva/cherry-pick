git cherry-pick is almost same as git merge except it only merges at a specific commit, not subsequent commit. For example, commit a, commit b. If you want commit a, cherry-pick --edit a.<br/>
git cherry-pick --edit <hash>  // stay on your current branch to merge files into your current branch from another branch.<br/>
Solve merge conflict<br/>
git add .<br/>
git commit -m <br/>
git push<br/>

git cherry-pick -n <hash>  // you can work on current branch after commit<br/>
solve merge conflict<br/>
git add .<br/>
git commit -m<br/>
git push<br/>



