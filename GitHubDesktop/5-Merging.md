# Merging

## Merging two or more branches

To merge one branch into another, checkout the branch that you want to merge to
(See [Branches](4-Branches.md) on how to do this), then switch to the `history`
view:

![Branch History](../resources/GitHubDesktop/history.png)

Now, choose the branch that you want to merge into this one:

![Compare Branch](../resources/GitHubDesktop/compare_branch.png)

Finally, after verifying that all of the changes are what you want to merge,
click the `Merge into <branch>` button:

![Merge Button](../resources/GitHubDesktop/merge_button.png)

## Merge Conflicts

When a merge conflict occurs, GitHub Desktop will tell you that they are present:

![Merge Conflict](../resources/GitHubDesktop/merge_conflict.png)

When this happens, if you click the `Merge into <branch>` button, you will see
something like this dialog pop up:

![Merge Conflict Dialog](../resources/GitHubDesktop/conflict_dialog.png)

At this point, you will need to open up your editor of choice to resolve the
conflict. Once you have, you can merge as normal.

## Rebasing

To rebase one branch onto another, open the `Branch` dropdown and select
`Rebase current branch...`:

![Rebase Dropdown](../resources/GitHubDesktop/rebase_dropdown.png)

From here, select the branch you want to rebase onto and click the `Start rebase`
button:

![Rebase Button](../resources/GitHubDesktop/rebase_button.png)
