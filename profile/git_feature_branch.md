# Create a feature branch

1. `cd YOUR_FORK_DIR`
1. `git checkout develop`
1. `git fetch upstream`
1. `git rebase upstream/develop`
1. `git branch -c BRANCH_NAME`
1. `git push`