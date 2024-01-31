# STAGE & SNAPSHOT

## Working with snapshots and the Git staging area

Show modified files in the working directory, staged for the next commit

```
git status
```

Add a file as it looks now to your next commit (stage)

```
git add [file]
```

Unstage a file while retaining the changes in the working directory

```
git reset [file]
```

Diff of what is changed but not staged

```
git diff
```

Diff of what is staged but not yet committed

```
git diff --staged
```

Commit your staged content as a new commit snapshot

```
git commit -m "[descriptive message]"
```

# Replace `[file]` with the actual file name and `[descriptive message]` with a meaningful commit message.
