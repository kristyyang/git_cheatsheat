# Concise Git Tutorial

## Files

Check git status:

```bash
git status
```

Simplified version: `g st`

Stage a change:

```bash
git add [file name]
```

Simplified version: `g a [file name]`

Stage all changes

```bash
git add --all
```

Simplified version: `g aa`

Commit a change

```bash
git commit -m [commit message]
```

Simplified version: `g cmsg [commit message]`

## Branches

Checkout master:

```bash
git checkout master
```

Simplified version: `g cm`

Make a new branch:

```bash
git branch [branch name]
```

Simplified version: `g br [branch name]`

Checkout the new branch:

```bash
git checkout [branch name]
```

Simplified version: `g ck [branch name]`

Make a new branch and checkout that branch (combine the two previous steps):

```bash
git checkout -b [branch name]
```

Simplified version: `g cb [branch name]`

Delete a branch:

```bash
git branch -d [branch name]
```

Simplified version: `g bd [branch name]`

## Work with the remote server

Upload a branch:

```bash
git push -u origin [branch name]
```

Simplified version `g puo [branch name]`

Delete a remote branch:

```bash
git push -d origin [branch name]
```

Simplified version: `g pdo [branch name]`

```bash
clean the terminal line `
```

Control + U

```bash
clean the terminal page`
```

Control + L

```bash
g ck --track origin/cutiekristy
```
