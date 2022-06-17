# git-cheatsheet

**Commit changes**
```
git add --all
git commit -am "<message>"
git push origin master
```

**Get the URL that a local Git repository was originally cloned from:**

```
git config --get remote.origin.url
```

**Push an empty commit (for example to trigger a Drone automation):**

```
git commit --allow-empty -m "Empty-Commit"
```
