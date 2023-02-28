# CAB202 Tutorials

## Setup

### Creating a repository

1. Click `Use this template` then `Create a new repository`.
2. Select `Private` repository and `Include all branches`.

### Cloning the repository locally

It is recommended that you setup GitHub in VS Code using this guide: [Working with GitHub in VS Code](https://code.visualstudio.com/docs/sourcecontrol/github).

This will allow you to manage the repository through VS Code.

To clone the repository within VS Code, see [Clone and use a GitHub repository in Visual Studio Code](https://learn.microsoft.com/en-us/azure/developer/javascript/how-to/with-visual-studio-code/clone-github-repository?tabs=create-repo-command-palette%2Cinitialize-repo-activity-bar%2Ccreate-branch-command-palette%2Ccommit-changes-command-palette%2Cpush-command-palette).

## Using the branches

### Navigating branches

Each tutorial/extension task lives in it's own branch. To access these branches, you must "checkout" the particular branch.

1. Select the `Source Control` icon
2. Expand the `Branches` menu.
3. Click the rightward arrow to "fetch" a branch from GitHub locally. These branches will look like: `origin/<branch name>`. Once selected, you will be prompted to name that branch, and you can simply press <kbd>Enter</kbd> to use the default name.

You can now download the task files and copy them into this directory.

**Make sure to switch to the appropriate branch each week!**

### Tracking files

After adding the files to this directory, you must tell git to "track" them. This is done through the `Source Control` menu and clicking the `+` icon
(`Stage Changes`) and then committing your changes.

**Each commit requires a message, so be sure to be informative!**

For the initial commit, use the message `"Initial commit"`.

### Pushing commits to remote

Each commit maintains a history of the files that are in that branch. These commits are stored locally and must be synced with the remote branch (on GitHub) for external access.

To "push" your changes onto a remote repository (like GitHub), click `Sync changes`. Alternatively, you can click the chasing arrows icon (two circular arrows) on the Status Bar in VS Code (bottom-left of VS Code).

Additional support for version control can be found here:
[Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview#_working-in-a-git-repository)
