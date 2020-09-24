# Merging

1. Create two branches, `source-branch` and `target-branch`
2. Check out `source-branch`
3. Modify a file
4. Commit the changes
5. Merge `source-branch` to `target-branch`

---------

## ***Hints***

<details>
    <summary>Hint 1</summary>
    <blockquote>
    <details>
        <summary>Command Line</summary>

Revisit [this document](../CommandLine/4-Branches.md) if you are having trouble
creating branches.
    </details>
    <details>
        <summary>VSCode</summary>

Revisit [this document](../VSCode/4-Branches.md) if you are having trouble
creating branches.
    </details>
    <details>
        <summary>GitHub Desktop</summary>

Revisit [this document](../GitHubDesktop/4-Branches.md) if you are having trouble
creating branches.
    </details>
    </blockquote>
</details>

<details>
    <summary>Hint 2</summary>
    <blockquote>
    <details>
        <summary>Command Line</summary>

Branches are merged using the `git merge [<from commit>...]` command.

This is either in the form of `git merge [from]` to merge to the currently checked
out branch or `git merge [from] [to]`
    </details>
    <details>
        <summary>VSCode</summary>

You can merge branches by using the `Merge branch...` button in the
`More Actions...` drop down:

![Merge Button](../resources/VSCode/merge_branch.png)
    </details>
    <details>
        <summary>GitHub Desktop</summary>

You can merge branches by selecting a branch in the `History` section and
clicking the `Merge into <branch>` button:

![History](../resources/GitHubDesktop/history.png)

![Merge Button](../resources/GitHubDesktop/merge_button.png)
    </details>
    </blockquote>
</details>
