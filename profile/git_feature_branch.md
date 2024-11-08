# Create a feature branch

A branch is where you should write your own new code. This branch is in your BDSIM repostiroy fork. 

1. `cd YOUR_FORK_DIR`
1. `git checkout develop`
1. `git fetch upstream`
1. `git rebase upstream/develop`
1. `git checkout -b BRANCH_NAME`
1. `git push`
1. Develop your code

If you wish to return to develop or another brach

* `git checkout develop`
