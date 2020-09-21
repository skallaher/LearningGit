# What is Git

Git is what is called a `version control system`. This means that Git is
responsible for tracking and maintaining the changes made to files over time.

Below, we'll discuss some of the different parts of Git.

---------

## Repository

A set of files in a directory. This is the main structure of Git and is defined
by a hidden `.git` directory containing a bunch of metadata.

***Note:***
You should not edit any files in the `.git` directory unless you are certain of
what you are doing.

## Commits

Git tracks changes using things called `commits`. A commit represents a set of
additions and deletions from the previous commits. Each commit has what is called
it's `parent` which determines what its changes are based off of.

## Commit Graph

The set of commits in your Git history is called the commit graph.

***Additional Information:***
A graph is a common software data structure which connects different nodes with
edges (Don't fret too much over the details of this). In the case of Git, the
nodes are commits and the edges are connections to the commit's parent(s).

## Staging

Files with Git exist in one of four states

### Untracked

These are files that Git sees in your repository, but hasn't been told to do
anything with them. When you create a new file it will become untracked.

### Unstaged

These are files which Git has detected changes in, but will **not** be included in
the next commit.

### Staged

These are files which **will** have its changes included in the next commit.

### Committed

Git knows about these files, and is tracking them, but they do not have any
changes from the previous commit.

---------
