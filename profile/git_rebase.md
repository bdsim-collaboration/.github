# BDSIM rebase instructions

If upstream repository has updated

1. `git fetch upstream`
1. `git checkout YOUR_FEATURE_BRANCH`
1. `git rebase upstream/develop`
1. Check your code operates correctly and run test suite
1. `git push --force`
