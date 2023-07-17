# CAB202 Tutorials

## Setup

### Using this repository

1. Click `Use this template` then `Create a new repository`.
2. Check `Include all branches`.
3. Name the repository.
4. Select `Private` repository.

### Using git within VS Code

If this is your first time using git, I recommend using the [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) extension to graphically interface with git within VS Code.

This will allow you to manage this repository through VS Code.

Make sure to sign-up for the [GitHub Student Developer Pack](https://education.github.com/pack) for a free GitLens+ Pro license!

### Making a copy of the repository on your computer (Cloning the repository locally)

To clone this repository within VS Code, see [Clone and use a GitHub repository in Visual Studio Code](https://learn.microsoft.com/en-us/azure/developer/javascript/how-to/with-visual-studio-code/clone-github-repository?tabs=create-repo-command-palette%2Cinitialize-repo-activity-bar%2Ccreate-branch-command-palette%2Ccommit-changes-command-palette%2Cpush-command-palette).

After this step, you should see `main` in the bottom-left of the Status Bar in VS Code. 

## How to use this repository for CAB202 exercises

### How to navigate exercises

Gradescope's _GitHub upload_ requires you to separate each exercise into it's own branch. 
For our purposes, this is like having separate folders for each exercise.

When working on a particular exercise, you must "checkout" it's corresponding branch. 

1. In the Status Bar, click "main" (this is the `Source Control Checkout` button). You should receive a prompt to `Select a branch or tag to checkout`.
2. Select the appropriate branch on the remote server (GitHub). This should look like `origin/extension-1`. This will create a local copy of that branch, which you can now work on.

You may now copy the relevant exercise files into this directory. 

Although there are 20 branches in this repository, git will only create one folder for the repository on your computer. When you checkout a branch, git will only show the files within that  branch and safely store the data from other branches within the hidden `.git` folder. Do not modify this folder! 

**Make sure to switch to the appropriate branch each week! The VS Code indicates the selected branch on the Source Control Checkout button in the Status Bar.**

### How to upload files to GitHub

Once you have selected a branch and copied the exercise into your project directory, you must tell git to "track" those files (to include them in the upload). You should see a "U" next to any untracked files.

1. Select the `Source Control Repositories` menu in the Side Bar.
2. Expand the `Source Control` menu.
3. Under changes, click the `+` icon to stage changes; you can either stage all changes, or select individual files. Both new (untracked) files and modified (previously tracked) files will appear here. 
4. Once all files have been staged, add a commit message, and click the `Commit` button.

I recommend making an "initial commit" when you first checkout a branch and copy the exercise files. This will make the template text within that exercise a starting point for git to begin tracking your file. 
For the initial commit, use the message `"Initial commit"`.

### Uploading commits to GitHub

Each commit maintains a history of the files that are in that branch. These commits will be stored locally until they are synced with the remote branch (GitHub) for external access:

```bash
# (Local)      (GitHub)
  <branch> <-> origin/<branch>
```

You can "upload" all your commits to GitHub by "pushing" these commits to the remote branch. 

After each commit, the Commit button will say, `Sync Changes`, you can click this to synchronise commits on GitHub. Alternatively, you can click the chasing arrows icon (two circular arrows) on the Status Bar, on the right-hand side of the branch name.

Additional support for version control can be found here:
[Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview#_working-in-a-git-repository)
