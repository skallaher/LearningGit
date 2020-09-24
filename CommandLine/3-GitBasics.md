# Git Basics

## Making a commit

To make a commit, first you will need to add all of the files that you want to
be part of the commit to the staging area. To see the current state of your
repository, use

```bash
git status
```

This will show you which files have been changed or added, and in what part of the
staging process they are in. For example:

```txt
On branch master

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified: README.md

no changes added to commit (use "git add" and/or "git commit -a")
```

Let's commit this `README.md` file:

```bash
git add README.md
git commit
```

You will notice that in the above example output for `git status`, that git
suggests `git commit -a`. This command adds **all** files (except untracked files)
to the staging area before creating a commit. While this may seem like a very
convenient shortcut, you should always be aware of which files you will be
committing and be intentional of what you commit.

If you have any files that are staged which you no longer want to commit, you
can unstage them using the `reset` command:

```bash
git reset -- <filename>
```

## Commit Messages

You may have noticed in the [previous section](#making-a-commit) that running
`git commit`, a text editor opens where you can edit the commit message. However,
we can add the `-m <message>` argument to the command in order to skip openning
the text editor and set the message directly. For example:

```bash
git commit -m "Here's my commit message!"
```
