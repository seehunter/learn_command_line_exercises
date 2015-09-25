Git Troubleshooting While Learning
==============================================

#1. Create a repo locally, then push it to github

#2. Create a github repo, then clone it locally
---

>mkdir <new repo>
>cd <new repo>
>git status

git status
fatal: Not a git repository (or any of the parent directories): .git

>git init
><add, create, files, dirs>
>git add <file or dir>
>git commit -m "this is what I changed.."
>git push

fatal: No configured push destination.

..so you must point your local working dir to the remote:

>git remote add origin git@github.com....
>git push -u origin master
><more changes, adds, commits>
>git push

NOTE: The above fails miserably if a Readme is present 
on remote GitHub origin and on local branch. Once
the remote Readme is removed, then you must undo 
the damage and redo the push to align with origin
master branch on the remote Github:

>git remote rm origin
>git remote add origin <ssh url>
>git push -u origin master

all is happy now and future pushes from within
the local branch may simply be:

>git push

make some changes, add them, commit them

>git add <filename>
>git commit -m "here is what I added"
>git status

On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)
nothing to commit, working directory clean

>git push    or...
>git push -u origin master
>git status

On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working directory clean

