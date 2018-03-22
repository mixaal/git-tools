# git-tools
git tools for automatic branching and automatic branch deletion once merged into develop branch

## Simple Usage

### Feature development start

```
git_reset # on a sunny day
git commit -a ...
git commit -a --amend
git_push
```

### Feature fix

```
git_reset
git_checkout feature_name
git rebase origin/develop
git add ... # resolve conflicts
git rebase --continue
git_push
```


