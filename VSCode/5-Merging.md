# Merging

## Merging two or more branches

To merge one branch into another, open the `More Actions...` menu:

![More Actions](../resources/VSCode/action_menu.png)

Then select the `Branch` submenu:

![Branch Menu](../resources/VSCode/branch_dropdown.png)

Choose `Merge Branch...` and select the branch to merge into the one you currently
have checked out.

![Merge Branch](../resources/VSCode/merge_branch.png)

## Merge Conflicts

In the event of a merge conflict, VSCode will inform you that the conflict has
occurred with a notification and will show which files have conflicts.

![Conflict Notification](../resources/VSCode/merge_conflict_notification.png)

![Conflicting Files](../resources/VSCode/merge_conflict_files.png)

Within the files that have conflicts, Git will add annotations to indicate which
lines are conflicting, which VSCode will render something like this:

![Conflict Annotations](../resources/VSCode/conflict_annotation.png)

These annotations should be removed when you resolve the merge conflict. Once you
have resolved the conflicts, you will need to stage all of the conflicted files
and then complete the merge by clicking the `Commit` button.

Somewhat frustratingly, VSCode does not natively support aborting a merge.

## Rebasing

VSCode does not natively support rebasing.
