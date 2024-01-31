# SHARE & UPDATE

## Retrieving updates from another repository and updating local repos

Add a git URL as an alias

```
git remote add [alias] [url]
```

Fetch down all the branches from that Git remote

```
git fetch [alias]
```

Merge a remote branch into your current branch to bring it up to date

```
git merge [alias]/[branch]
```

Transmit local branch commits to the remote repository branch

```
git push [alias] [branch]
```

Fetch and merge any commits from the tracking remote branch

```
git pull
```
