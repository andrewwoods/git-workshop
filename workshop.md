# Workshop

This is a hands-on, in-person workshop

## Create a Repo(sitory)

### init

Adds a .git folder to make it a git enabled project


### clone

copies a remote repository to your system,
with a complete log of all the commits.


## Adding Content

### add

* Add a new file to the index (staging area)
* Add a change to an existing file to the index

Add all the changes for a file

```bash
$ git add filename.txt
```

Interactively select the changes you want to add for a file

```bash
$ git add -p filename.txt
```


### commit

* standard commit
* -a : commit everything
* -m : provides a message on the command line

**tracked files** are files that git already knows about

```bash
# Normal commit - this opens an editor for you to add your message
$ git commit

# Commit all tracked files without needing to run 'git add' first
$ git commit -a

# Use this message and don't open the editor
$ git commit -m 'Just a short message'
```

### status

Show which files have been changed, added, or untracked. This is easily the command I run the most.

```bash
$ git status
```

### diff

Normal use of `diff` command compares the local files to your local repository

```bash
$ git diff
```

Compare your local files to staged files

```bash
$ git diff --staged
```

Get the names of the files you changed

```bash
$ git diff --name-only
```



## Removing Content


## Branches

### Creating Branches

### Merging Branches


## Working With Others

### Creating Remotes

### Interacting With Remotes


## Workflow

### Feature Branches


## Controlling Commits


## Configuration

### .gitconfig


