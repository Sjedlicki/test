List of commands

**git init** - Initialize (create) a new local repository. Only do this once per project.

**git add <file/folder>** - Add a file or folder to the staging area. Include the name or path of the file or folder. Do not include the angle brackets (<, >).

**git commit -m '<message>'** - Commit the staging area changes as a snapshot on the repository timeline. Replace <message> with a description of the changes you're making. Do not include the angle brackets (<, >).

**git reset HEAD <file>** - Remove a file from staging.

**git rm --cached -r .** - Recursively(-r) remove ALL(.) files from staging.

**git push** - Push (copy) your committed changes to the remote repositroy (i.e. GitHub).

**git pull** - Pull (copy) changes from a remote (i.e. GitHub) repository to your computer.

**git status** - View the current changes and staging area

**git diff <file>** - View changes to a file that is unstages.

**git diff --staged <file>** - View changes to a file that is staged. (What lines were added, removed, and modified?)

**git log** - View list of commits in the repository snapshot timeline.

**git show <commit hash>** - View details about a particular commit.

**git remote -v** - View which remote repository (i.e. GitHub repository) this repo is linked to, if any.

**git remote add origin <GitHub URL>** - Link to a remote repository (i.e. a GitHub repo).

**git push -u origin master** - The first push to the remote repository. Sets up for future pushes with simply git push.

**git clone <GitHub URL>** - Download and link a copy of a remote GitHub repository onto your computer. This creates a new folder on your computer.

**git checkout <commit hash>** - temporarily go back to a commit

**git checkout master** - return to the latest commit

**git reset --hard <commit hash>** - undo back to an old commit

**git push --force** - update GitHub after a reset

**git reset --hard origin/master** - reset local repo to GitHub

**git checkout -- <file>** - undo all changes to a file