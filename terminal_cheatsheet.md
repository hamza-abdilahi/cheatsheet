`pwd (print, working, directory)` - tells you what directory you are currently in.

`cd` allows you to change directory.

`cd ..` goes up a directory.

`cd -` - returns to the last directory you were in.

clear - to clear the terminal.

`ls` - a list of the current directory.

`ls -a` lists all contents of the current directory, including hidden files.

`cp` - similar to mv but creates a duplicate instead of a move.

### The commands needed to initialise a repo, connect it to a remote and push your changes are as follows:

1. `mkdir newProject` - creates our directory.
2. `cd newProject` - moves into our new folder.
3. `git init` - initialises our new Git repository.
4. `touch newFile.txt` - creates a new text file.
5. `nano newFile.txt` - allows us to edit our text file in the terminal.
6. `git add newFile.txt` / `git add .` - tells our local repo to track this new file. `.` will select all modified files.
7. `git commit -m "our commit message"` - commits our file to our local repo.

### Create a GitHub repo in your browser.

1. `git remote add origin <GIT URI of new remote repository>` - connects your local and remote repos.
2. `git branch -M main` - renames the current branch to `main`.
3. `git push -u origin main` - pushes the local changes to the remote.

### To commit changes to your local repo and to push changes to a remote repo once you have everything set up:

1. `git add ...` - add the files which have been changed that you want to commit (`.` specifies all files, `git status` can show you modified files).
2. `git commit -m "..."` - commits the added files from above to your local repo.
3. `git push` - pushes changes to your remote repo. 