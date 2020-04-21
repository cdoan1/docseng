# git helper

## Sync your fork to Upstream

1. sync your fork to upstream

```
git clone git@github.com:YOUR-USERNAME/YOUR-FORKED-REPO.git
```

2. Add remote from original repository in your forked repository

```
cd into/cloned/fork-repo
git remote add upstream git://github.com/ORIGINAL-DEV-USERNAME/REPO-YOU-FORKED-FROM.git
git fetch upstream
```

3. Updating your fork from original repo to keep up with their changes:

```
git pull upstream master
```

NOTE: Alternatives

```
git rebase upstream master
git merge upstream/master

```


4. Update your fork repo

```
git push
```

NOTE: Alternatives

```
git push origin master
```

## Rebase Squash your branch

1. Rebase by branch onto master

```
git checkout <development branch>
git rebase master
git push origin +HEAD
```

## Rebase and Squash your commits

```
git checkout <development branch>
git rebase -i HEAD~n
git push origin +HEAD
```


