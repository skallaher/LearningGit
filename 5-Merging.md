# Merging

Merging is the process of taking two different branches and bringing their changes
together into one branch. This is usually done for the following reasons:

- Bringing WIP changes into the main branch since they are completed
- Getting a WIP branch up to date with the main branch after the main branch is
updated
- Incorporating changes from one WIP branch into another WIP branch to ensure that
their changes are compatible or because their changes are related.

Though this is by no means an exhaustive list.

In Git, a merge creates a new commit on the target branch (the branch being
merged into) which has two or more parent commits representing the commits which
were merged together. Merge commits, just like standard commits, have a commit
message which defaults to `Merge of branch X into branch Y`.

<!-- TODO: Give a visual of this operation -->

## Merging two or more branches

How this operation is performed is specific to which tool you are using, as such,
see the relevant document for your tool.

- [Command Line](CommandLine/5-Merging.md#merging-two-or-more-branches)
- [VSCode](VSCode/5-Merging.md#merging-two-or-more-branches)
- [GitHub Desktop](GitHubDesktop/5-Merging.md#merging-two-or-more-branches)

## Merge Conflicts

A merge conflict is an event that happens when you attempt to merge two branches
which both change the same file and Git doesn't know how to automatically resolve
the differences. These sorts of merges require intervention to resolve.

Each of the following tools provides you with different mechanisms for resolving
these issues:

- [Command Line](CommandLine/5-Merging.md#merge-conflicts)
- [VSCode](VSCode/5-Merging.md#merge-conflicts)
- [GitHub Desktop](GitHubDesktop/5-Merging.md#merge-conflicts)

## Rebasing

***Disclaimer:*** Rebasing is a more complex and advanced topic. It is included
here for completeness.

Rebasing, similar to merging, is a mechanism for bringing changes from one branch
to another. However, rebasing also allows for modifying the commit history and
should be used with care.

When rebasing a branch onto another, the commits in the source branch are replayed
ontop of the commits of the target branch one at a time. This process also allows
for modifying commits and commit messages, squashing commits together, or ignoring
specific commits.

The instructions on how to perform these operations for each tool are as follows:

- [Command Line](CommandLine/5-Merging.md#rebasing)
- [VSCode](VSCode/5-Merging.md#rebasing)
- [GitHub Desktop](GitHubDesktop/5-Merging.md#rebasing)
