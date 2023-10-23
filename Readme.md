## GitHub Authentication

GitHub authentication is the process of verifying the identity of users or applications attempting to access resources on GitHub. GitHub offers several authentication methods to ensure the security and integrity of user accounts and data. 

### Two-Factor Authentication (2FA)
- GitHub offers 2FA as an additional security layer for user accounts. This involves a second authentication factor, typically a time-based one-time password (TOTP) generated by a mobile app, in addition to the password.

### SSH (Secure Shell) Keys
- For Git operations (e.g., cloning repositories) over SSH, you can use SSH keys for authentication. GitHub allows users to associate SSH keys with their accounts for secure access.

### Username and Password
- This is the most basic form of authentication. Users provide their GitHub username and password to log in. However, it's generally not recommended for automated scripts or applications because it involves sharing sensitive credentials.

## Github commands

Github commands and usage:

- [git version] - to verify Git was installed on your computer termina
- [git init] - initialize an existing directory as a Git repository
- [git status] - show modified files in working directory, staged for your next commit
- [git clone] - is used for just downloading exactly what is currently on the remote repository and saving it in your machine's folder where that project is placed. (Only one time)
- [git fetch] - is the command that tells the local repository that there are changes available in the remote repository
without bringing the changes into the local repository.

- [git pull] -  downloads the changes and merges them into your current branch. (Can be multiple time if there is new
changes on the branch in the repo)
- [git add] - Stage the all the file for commit to your local repository by the following command.
- [git reset (file)] - unstage a file while retaining the changes in working directory
- [git diff] - diff of what is changed but not stage
- [git commit -m "Create changes on README file"] - Commit the file that you’ve staged in your local repository.
- [git push origin main] - Push the changes in your local repository to GitHub
- [git merge] - The "merge" command is used to integrate changes from another branch.
- [git branch] - list your branches. a * will appear next to the currently active branch
- [git log] - show all commits in the current branch’s history
- [git rm (file)] - delete the file from project and stage the removal for commi


## 4 Github commands I think will use the most in a real project and why.

In a software development project, the 'git clone' command is crucial for initiating a new project or accessing an existing repository, enabling the creation of a local copy of a remote repository on your machine to establish your development environment or facilitate collaboration. The 'git pull' command plays a pivotal role in keeping your local copy synchronized with the remote repository by fetching and merging changes, thus ensuring you're working with the latest code. Complementing this, the 'git add' and 'git commit' commands work in tandem to save local changes and document them with descriptive messages, making your work available for others to collaborate on and preserving it in the project's history. Finally, the 'git push' command serves as the conduit for uploading these changes to the remote repository, fostering effective code sharing and collaborative development among team members, thereby solidifying its integral role in the overall development workflow.