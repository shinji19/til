# Git cheatsheet

## Tracking

```sh
# create branch
git checkout -b new-branch upstream/target-branch
# exist branch
git branch -u upstream/target-branch current-branch
# check
git branch -vv
```

## LFS

```sh
git lfs fetch --all
```
