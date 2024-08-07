# Using Git GUI

The Git GUI provides a graphical interface for interacting with Git repositories. Here’s an overview of the elements and how to use them:

## Current Branch: Main
**Current Branch:** Indicates the branch you are currently working on. In this case, it's `main`. You can switch branches or create new ones from here.

## Unstaged Changes
**Unstaged Changes:** This section lists all the files that have been modified but not yet staged for commit. These changes are tracked by Git but are not part of the commit snapshot.

## Staged Changes
**Staged Changes:** This section lists all the files that have been added to the staging area. These changes are ready to be committed to the repository.

## Rescan
**Rescan:** This button refreshes the view to reflect the current state of your working directory. It updates the lists of unstaged and staged changes.

## Stage Changed
**Stage Changed:** This button stages all the currently unstaged changes. Staging a file means it’s marked to be included in the next commit.

## Sign Off
**Sign Off:** Adds a `Signed-off-by` line to your commit message. This is often used to indicate that the committer agrees to the Developer Certificate of Origin (DCO), which is a statement that you have the right to submit the changes and that you are willing to have your work incorporated into the project.

## Commit
**Commit:** This button commits the staged changes to the repository. When you click it, a dialog will appear asking for a commit message. The commit message should describe the changes you have made.

## Push
**Push:** This button pushes your committed changes to a remote repository, such as GitHub. You need to specify the remote repository and branch if they are not already configured.

## Amend Last Commit
**Amend Last Commit:** This allows you to modify the most recent commit. You can add new changes to it or change the commit message. This is useful if you realize you forgot to include something in your last commit or made a mistake in the commit message.

# Using Git GUI Workflow

Here’s a typical workflow using the Git GUI:

1. **Check Unstaged Changes:** Look at the list of unstaged changes to see which files have been modified.
2. **Stage Changes:** Select the files you want to include in your next commit and click `Stage Changed` to move them to the staged changes area.
3. **Commit Changes:** Once you have all the changes you want to commit in the staged area, click `Commit`. Enter a descriptive commit message and finalize the commit.
4. **Push Changes:** After committing, click `Push` to send your changes to the remote repository. This ensures your changes are backed up and shared with others if you're collaborating.
5. **Amend Last Commit:** If you need to make changes to your last commit, use the `Amend Last Commit` option to adjust the commit message or add more changes to it.

# Additional Tips

- **Navigating Branches:** You can create, switch, and manage branches through the Git GUI. This is helpful for managing different lines of development.
- **Pulling Changes:** Make sure to regularly pull changes from the remote repository to keep your local copy up to date with others’ work.
- **Resolving Conflicts:** If there are conflicts when merging or pulling changes, the Git GUI can help you visualize and resolve them.
