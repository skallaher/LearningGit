# Branches

A branch in Git is a separate chain of commits off of the main set of commits.
The default, or main, branch is considered the latest good set of code that all
other code should be compared against.

Under the hood, branches are simply pointers at a commit, though they can
conceptually be viewed as a collection of commits.

![Git Branches](resources/git_branches.svg)

## Why use a branch

Branches in Git allow you to keep your changes separate from someone else's,
meaning that each developer can work without worrying about affecting, or being
affected by, anyone else.

It also allows the separation of different tasks so that they don't accidentally
get intertwined.

## Creating a branch

The creation of a branch is tool specific, please see the relevant document for
your tool of choice.

- [Command Line](CommandLine/4-Branches.md#creating-a-branch)
- [VSCode](VSCode/4-Branches.md#creating-a-branch)
- [GitHub Desktop](GitHubDesktop/4-Branches.md#creating-a-branch)

## Branches vs Forks

We've just discussed what branches are and why they're useful. Forks are a
similar, yet different concept that is only valuable at a remote (We'll cover
these later).

A fork completely copies the entire repository, including all of its branches, to
a new repository. This is useful if you don't have write access to the original
repository as merges can be performed across repositories within a remote.
