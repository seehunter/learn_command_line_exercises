>#To discover the name of the computer your commandline cursor is sitting at, type the following:

* hostname
* see a string displayed
* this is the name assigned to this computer
* example: Topaz-Sue.local

#English Questions

What host are you on?
> To tell someone else what host I am on, I would run the following:

hostname

> This will display a string which is the name of my computer hosting this iTerm terminal window for the commandline prompt I am sitting at. 

> My computer name or (host name) is Topaz-Sue.local

Are you on your local machine?

> To tell if my iTerm terminal commandline cursor is sitting on my local branch pointing to origin master branch on GitHub, I would type the following and look for a directory named .git in my current directory:

ls -aF

> If it displays ".git/", then I know I am sitting in my local branch pointing up to origin master on GitHub.
> If no ".git/" is listed, then I would type:

git status 

cd .. 

ls -aF 

git status 

cd .. 

ls -aF 

> The status will reveal what state my git sharing is in (if any exists), and by walking up the tree of directories I will soon discover the local branch pointing to origin master on GitHub.


> 
