to rename a branch do git branch -m <branchname> (git branch -m=modify <branchname>)

after rename you must delete old branch from remote repo to do so git push origin --delete <oldbranchname>

but now the branch has an upstream of the old branch you must set it's proper upstream with it's new name i used

git push --set-upstream origin <new-branch-name>