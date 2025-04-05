# Git Lab 2
![My Image](images/pic.png)
Remove branches locally and remotely
-Locally
git branch -d dev
git branch -d test
-Remotely
git push origin --delete dev
git push origin --delete test 


//Checkout another branch without committing changes
git checkout branch-name --ignore-other-worktrees 

//Tell me how to delete tag locally and remotely.
git tag -d v1.7
git push origin --delete tag v1.7
