Chapter Four Do More
======
*Make 20 other directories inside the temp directory in various levels. Go look at them with a graphical file browser.
*Make a directory with a space in the name by putting quotes around it: mkdir "I Have Fun"
*If the temp directory already exists then you'll get an error. Use cd to change to a work directory that you can control and try it there. On windows Desktop is a good place.

Chapter Four English Questions
======
1. Can you make a temp directory?
---
>Yes, to make a tmp directory at my current cursor location, I would type the following:
`mkdir tmp`
> this produces: Topaz-Sue:davinci_coders_t3_2015 $ mkdir tmp
>
>Topaz-Sue:davinci_coders_t3_2015 $ ls
>Icon?                          my_name.txt
>building_the_toolbelt_t3_2015/ practice/
>homework/                      tmp/
>in_class/


2. Can you make a log directory in your class directory?
---
>Yes, to make a log directory in my class directory I would first get to my class directory, see if the log directory is already there or not, create it, then see it got created with the following set of commands:
`cd /Users/Topaz/workspace/davinci_coders_t3_2015`

`ls -altF`

`mkdir log`

`ls -altF`

>this produces: 
Topaz-Sue:davinci_coders_t3_2015 $ cd /Users/Topaz/workspace/davinci_coders_t3_2015


Topaz-Sue:davinci_coders_t3_2015 $ ls -altF
total 616
drwxr-xr-x@ 11 Topaz  staff   374 Sep 25 16:50 ./
drwxr-xr-x   2 Topaz  staff    68 Sep 25 16:50 tmp/
-rw-r--r--@  1 Topaz  staff  6148 Sep 23 22:24 .DS_Store
drwxr-xr-x   4 Topaz  staff   136 Sep 23 20:46 in_class/
drwxr-xr-x  12 Topaz  staff   408 Sep 23 19:10 building_the_toolbelt_t3_2015/
drwxr-xr-x   4 Topaz  staff   136 Sep 22 20:26 homework/
drwxr-xr-x   6 Topaz  staff   204 Sep 21 20:12 practice/
-rw-r--r--   1 Topaz  staff    12 Sep 21 19:34 my_name.txt
drwxr-xr-x   6 Topaz  staff   204 Sep 21 19:20 .sync/
-rw-rw-rw-@  1 Topaz  staff     0 Sep 21 19:20 Icon?
drwxr-xr-x   6 Topaz  staff   204 Sep 14 21:26 ../


Topaz-Sue:davinci_coders_t3_2015 $ mkdir log


Topaz-Sue:davinci_coders_t3_2015 $ ls -altF
total 616
drwxr-xr-x@ 12 Topaz  staff   408 Sep 25 16:58 ./
drwxr-xr-x   2 Topaz  staff    68 Sep 25 16:58 log/
drwxr-xr-x   2 Topaz  staff    68 Sep 25 16:50 tmp/
-rw-r--r--@  1 Topaz  staff  6148 Sep 23 22:24 .DS_Store
drwxr-xr-x   4 Topaz  staff   136 Sep 23 20:46 in_class/
drwxr-xr-x  12 Topaz  staff   408 Sep 23 19:10 building_the_toolbelt_t3_2015/
drwxr-xr-x   4 Topaz  staff   136 Sep 22 20:26 homework/
drwxr-xr-x   6 Topaz  staff   204 Sep 21 20:12 practice/
-rw-r--r--   1 Topaz  staff    12 Sep 21 19:34 my_name.txt
drwxr-xr-x   6 Topaz  staff   204 Sep 21 19:20 .sync/
-rw-rw-rw-@  1 Topaz  staff     0 Sep 21 19:20 Icon?
drwxr-xr-x   6 Topaz  staff   204 Sep 14 21:26 ../


