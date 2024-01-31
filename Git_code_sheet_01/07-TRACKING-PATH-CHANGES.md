## TRACKING PATH CHANGES

# Versioning file removes and path changes

Delete the file from the project and stage the removal for commit

```
git rm [file]
```

Change an existing file path and stage the move

```
git mv [existing-path] [new-path]
```

Show all commit logs with an indication of any paths that moved

```
git log --stat -M
```
