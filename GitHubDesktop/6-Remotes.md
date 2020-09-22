# Remotes

## Fetching

To run a fetch, use the `fetch` command:

```bash
git fetch
```

This will output any branches that have updated on the remote since your last
fetch or immediately return if there are no updates.

## Pulling

To pull changes, utilize one of the following forms of the `pull` command:

```bash
git pull
git pull <remote name> <branch name>
```

The former command will pull the upstream, the branch on the remote that your
local branch is linked to, of your branch into the local checked out version.

The latter command will pull the given branch from the given remote into the local
checked out branch.

## Pushing

To push your changes up to the remote, use one of the forms of the `push` command:

```bash
git push
git push <remote name> <branch name>
```

The former command will either, depending on your configuration, push just the
branch you are currently on to its upstream (the branch it is linked to on the
remote), or push every branch to their upstreams.

The latter command will push the branch you are on to the given branch on the
given remote.
