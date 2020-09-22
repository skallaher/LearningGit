# Merging

## Merging two or more branches

<!--TODO: Convert to VSCode instructions-->
To merge one branch into another, use the `merge` command:

```bash
git merge <from branch> ...
```

This will merge the specified branch into the branch that you currently have
checked out. This will open up a text editor on success to edit the merge commit
message. Similar to commit messages, you can add the `-m <mesage>` argument to
write the message within the command.

```bash
git merge <from branch> -m "Merged X into Y. Here's some extra data."
```

## Merge Conflicts

<!--TODO: Convert to VSCode instructions-->
In the event of a merge conflict, Git will inform you that the conflict has
occurred and `git status` will show which files have conflicts.

<!-- TODO: Add git status example for a merge conflict -->

Within the files that have conflicts, git will add annotations to indicate which
lines are conflicting.

```txt
<<<<<<< current-branch
... lines from the existing file ...
=======
... lines from the new version ...
>>>>>>> merging-branch
```

These annotations should be removed when you resolve the merge conflict. Once you
have resolved the conflicts, you will need to add all of the conflicted files and
then run `git commit` to complete the merge.

At any point during this process, if you don't want to continue with the merge,
you can run `git merge --abort` to stop and revert back to before the merge began.

## Rebasing

<!--TODO: Convert to VSCode instructions-->
To rebase one branch onto another, use

```bash
git rebase <onto branch>
```

To perform a rebase and make edits to the history as you do so, use

```bash
git rebase -i <onto branch>
```

This will open a text editor where you can change how the rebase is performed.
See the documentation at the bottom of the file that is opened as to how to use
this feature.
