# INSPECT & COMPARE

## Examining logs, diffs, and object information

Show the commit history for the currently active branch

```
git log
```

Show the commits on branchA that are not on branchB

```
git log branchB..branchA
```

Show the commits that changed the file, even across renames

```
git log --follow [file]
```

Show the diff of what is in branchA that is not in branchB

```
git diff branchB...branchA
```

Show any object in Git in human-readable format

```
git show [SHA]
```
