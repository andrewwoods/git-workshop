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

Remove a file from the project

```bash
$ git rm filename.txt
```

Just like `add`, you'll run `commit` after removing a file.


## Branches

A branch is a workspace. They keep your work separate from your fellow contributors. Branches are a fundamental skill, that makes it possible to use other more advanced git commands.


### Creating Branches

Create a branch named `awesome`

```bash
$ git branch awesome
```

Switch to the `awesome` branch

```bash
$ git checkout awesome
```

You can do both steps with one command

```bash
$ git checkout -b awesome
```

Once your on a branch, make your edits and do your normal `add` and `commit` commands discussed above.


### Merging Branches

Merging a branch allows you to combine your  work, with the work from others. If you created your branch from master.

```bash
$ git checkout master
$ git merge branchname

```

Sometimes when performing a merge, you can get an error called **merge conflict** because git gets confused about how it should handle the change.


## Working With Others

### Creating Remotes

### Interacting With Remotes


## Workflow

### Feature Branches


## Controlling Commits


## Configuration

### .gitconfig


