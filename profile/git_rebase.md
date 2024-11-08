# BDSIM rebase instructions

If upstream repository has updated and you wish to incorperate these changes with your feature branch 

## On the terminal 

1. `git fetch upstream`
  1. `git checkout develop`
  1. `git rebase upstream/develop`
  1. `git push --force
1. `git checkout YOUR_FEATURE_BRANCH`
1. `git rebase develop`
1. Check your code operates correctly and run test suite
1. `git push --force`




## Using clion (easier if there are conflicts)