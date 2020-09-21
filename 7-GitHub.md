# GitHub

GitHub is one of many Git remote services and is currently the most popular. It is
widely used by open source projects for collaboration purposes. However, GitHub
(along with other remote services) has more collaboration tools than just a
Git repository. Among them are:

- Issue Tracking - A method for following the detection of bugs, request of
features, completion of tasks, or anything that requires a change of code.
- Projects - Collections of issues representing a larger project. This is useful
for monitoring the completion of different components.
- Pull Requests - Used to ask for changes in a branch or fork to be merged to
another branch or fork. In addition here, is the process of code review (more
on that later).
- Actions - A CI/CD (Continuous Integration/Continuous Deployment) tool. These
are most commonly used for automatically testing code and deploying it.

## Issues

An issue represents one of many things, but in the end represents something which
would need a change of code to resolve.

When creating a new issue, provide a succinct, useful title so that other
developers know what the bug or request is about. In addition, in the description
provide as much detail as possible about what needs to be changed. Some pieces
which are usually useful are:

- A brief description of either what the bug or feature is/what is being asked for
- For a bug, what is happening versus what should be happening
- Any relevant code snippets (You can use two sets of three back-ticks, `, to
create a code block which makes reading this much easier)

Issues in GitHub are assigned a number and represented throughout as `#<issue number>`. This can be used to reference them in other things such as commit
messages, other issues, and pull requests.

### Assignees

Assignees are used in issues to denote who is responsible for that issue. This
typically manifests in who is responsible for implementing the feature or fixing
the bug, however it can be used for other purposes as well.

### Labels

Issues can be given labels to help group them together or mark them as a
particular type. A single issue can be assigned any number of labels.

### Milestones

Milestones group issues together for tracking which issues are part of larger
initiatives, such as releases. ***Note:*** These are distinct from Projects.

## Projects

Projects allow for the grouping of issues, similar to milestones, but in a manner
which allows for a quick glance of the progress of each issue within the project.

## Pull Requests

A Pull Request is perhaps somewhat confusingly named, but is created as a way to
ask for changes from a branch or fork to be merged into a branch (usually the
main branch) in this repository. Similar to issues, pull requests are given a
number which can be used to reference them.

Creating a pull request should be done in a similar manner to creating an issue,
by providing a brief title that describes that changes enclosed in the pull
request as well as a detailed description of what the changes are intended to
accomplish. However, in addition here, any issues related to this pull request
should be mentioned in the description.

***Note:*** You can mention an issue with terms like `closes`, `fixes`, or
`resolves` just before the issue reference to automatically close the issue
when the pull request is merged.

### **Code Review**

Code review is the process of double checking code being merged into the
main branch for errors, confusing code, missing pieces, or any number of things.
This process is mainly intended to catch problems before they become part of
the main code base. Though, a beneficial side effect of this is also that more
people become familiar with the changes.

### Reviewers

Individuals who should perform a code review of the changes before they are
merged.

### Assignees

Similar to issues, the individuals who are responsible for the pull request. This
can represent developers who are responsible for merging the pull request or
otherwise need to view the pull request. There are also many other ways this
can be used, however, be sure that anyone who needs to review the code changes
is a `reviewer` rather than just an `assignee`.

### Labels

See `Labels` in the `Issues` section.

### Projects

See `Projects` in the `Issues` section.

### Milestones

See `Milestones` in the `Issues` section.
