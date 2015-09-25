#Git working area, staging, and repository

##Git Working Area
>The git working area is the local directory created by you or by a cloning process to store a set of files and subdirectories of files you wish to keep track of changes to. This working directory is the reference point for all local changes, local commits, as well as pushes and pulls to/from a remote repository if one exists.
>Typing "ls -aF" will display a .git subdirectory if you are sitting in your git working directory. 
>Typing "git log" will reveal the committed changes and comments about each committed change you made ever since the working directory was created (only git reset options will reset these log entries).

##Git staging
>Committing changes with "git add <file1>" is creating a staging area of all the changes currently intended to be the next set to be saved permanently to a remote repository. Changes occur locally as soon as you make them, but they are not staged for sharing until you add them to the staging area.

##Git repository
>The git repository is all the changes made to a set of files and subdirectories of files in your local git working directory. These changes are all tracked within a .git directory sitting in the top parent directory of the set of files (called a repo). The top parent directory is the working directory and the set of files and changes to them is the repo.

