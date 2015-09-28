Chapter Four Do More
======
*Make 20 other directories inside the temp directory in various levels. Go look at them with a graphical file browser.
>Topaz-Sue:learn_command_line_exercises $ ls -l chapter_4
>total 8
>-rw-r--r--  1 Topaz  staff  1454 Sep 28 08:41 Readme.md
>drwxr-xr-x  3 Topaz  staff   102 Sep 25 16:38 tmp/
>drwxr-xr-x  4 Topaz  staff   136 Sep 26 08:27 tree_of_twenty/
>
>(master) Sue Uyetake
>Topaz-Sue:learn_command_line_exercises $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises
>
>(master) Sue Uyetake
>Topaz-Sue:learn_command_line_exercises $ mkdir -p ./chapter_4/"another tmp"/"one A"/"two A"/"three A"/"four A"/"five A"/"six A"/"seven A"/"eight A"/"nine A"/"ten A"
>
>(master) Sue Uyetake
>Topaz-Sue:learn_command_line_exercises $ touch ./chapter_4/"another tmp"/"one A"/"two A"/"three A"/"four A"/"five A"/"six A"/"seven A"/"eight A"/"nine A"/"ten A"/.git.keep
>
>(master) Sue Uyetake
>Topaz-Sue:learn_command_line_exercises $ mkdir -p ./chapter_4/"another tmp"/"one BA"/"two BA"/"three BA"/"four BA"/"five BA"/"six BA"/"seven BA"/"eight BA"/"nine BA"/"ten BA"
>
>(master) Sue Uyetake
>Topaz-Sue:learn_command_line_exercises $ touch ./chapter_4/"another tmp"/"one BA"/"two BA"/"three BA"/"four BA"/"five BA"/"six BA"/"seven BA"/"eight BA"/"nine BA"/"ten BA"/.git.keep

*Make a directory with a space in the name by putting quotes around it: mkdir "I Have Fun"
>see above

*If the temp directory already exists then you'll get an error. Use cd to change to a work directory that you can control and try it there. On windows Desktop is a good place.
>Topaz-Sue:learn_command_line_exercises $ mkdir ./chapter_4/tmp
>mkdir: ./chapter_4/tmp: File exists
>
>(master) Sue Uyetake


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
>Yes, from wherever my cursor resides I can use an absolute path specification to create the log directory in my class directory.

Topaz-Sue:davinci_coders_t3_2015 $ pwd
/Users/Topaz/workspace/davinci_coders_t3_2015

Topaz-Sue:davinci_coders_t3_2015 $ cd

Topaz-Sue:~ $ pwd
/Users/Topaz

Topaz-Sue:~ $ mkdir /Users/Topaz/workspace/davinci_coders_t3_2015/tmp

Topaz-Sue:~ $ ls -F /Users/Topaz/workspace/davinci_coders_t3_2015
Icon?                          my_name.txt
building_the_toolbelt_t3_2015/ practice/
homework/                      tmp/
in_class/

