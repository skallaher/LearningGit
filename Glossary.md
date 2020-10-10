# Glossary

## Branch

***Note:*** The technical description here is that a branch is a pointer to
a commit somewhere in the commit graph, with the "logical branch" being all
of the commits discovered by following the parent pointers backwards from
this commit.

### HEAD

The HEAD "branch" is a special branch representing where you are in the
commit graph at the moment. You will likely only ever see this if you end
up in a "detached HEAD" state, meaning you aren't on a branch.

## Clone

The process of copying a repository from a remote to your local machine.

## Commit

A set of changes to files from the previous state of the repository which are
grouped together with a message attached.

## Fork

A complete copy of a repository to another repository, including all branches.

## Pull Request

A tool on GitHub to merge a branch (possibly from a fork) into another branch
of the repository which allows for code review and other methods to track work.

***Note:*** Other websites may have similar concepts to this under a different
name (such as a Merge Request on GitLab).

## Remote

An external instance of the repository, typically hosted on a website like
GitHub

## Repository

The base Git structure representing a collection of files.

## Working Directory

The local version of a repository which your files currently represent.

## Work In Progress (WIP)

WIP is a shorthand for Work In Progress, meaning that the changes are not yet
complete and should not be treated as the final product.
