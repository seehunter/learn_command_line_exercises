Chapter Five Do More
======
*cd to the joe directory with one command.
>Topaz-Sue:chapter_5 $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5
>
>(master) Sue Uyetake
>Topaz-Sue:chapter_5 $ cd ./tmp/stuff/things/frank/joe
>
>(master) Sue Uyetake
>Topaz-Sue:joe $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5/tmp/stuff/things/frank/joe
>
>(master) Sue Uyetake

*cd back to temp with one command, but not further above that.
> EITHER..
>Topaz-Sue:joe $ cd -
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5
>
>(master) Sue Uyetake
>Topaz-Sue:chapter_5 $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5
>
>(master) Sue Uyetake
>
> OR..
>
>Topaz-Sue:joe $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5/tmp/stuff/things/frank/joe
>
>(master) Sue Uyetake
>Topaz-Sue:joe $ cd ../../../../
>
>(master) Sue Uyetake
>Topaz-Sue:tmp $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5/tmp
>
>(master) Sue Uyetake

*Find out how to cd to your "home directory" with one command.
>Topaz-Sue:chapter_5 $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5
>
>(master) Sue Uyetake
>Topaz-Sue:chapter_5 $ cd ~
>
>Topaz-Sue:~ $ pwd
>/Users/Topaz

*cd to your Documents directory, then find it with your GUI file browser (Finder, Windows Explorer, etc.).
>Topaz-Sue:davinci_coders_t3_2015 $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015
>
>Topaz-Sue:davinci_coders_t3_2015 $ cd ~/Documents/
>
>Topaz-Sue:Documents $ pwd
>/Users/Topaz/Documents
>
>To see in GUI, click Finder-Documents

*cd to your Downloads directory, then find it with your file browser.
>Topaz-Sue:learn_command_line_exercises $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises
>
>(master) Sue Uyetake
>Topaz-Sue:learn_command_line_exercises $ ls ~
>Applications/     Library/          Public/
>Desktop/          Movies/           RubymineProjects/
>Documents/        Music/            sueProjects/
>Downloads/        Pictures/         workspace/
>
>(master) Sue Uyetake
>Topaz-Sue:learn_command_line_exercises $ cd ~/Downloads/
>
>Topaz-Sue:Downloads $ pwd
>/Users/Topaz/Downloads
>
>To see in GUI, click Finder-Downloads

*Find another directory with your file browser, then cd to it.
>Topaz-Sue:learn_command_line_exercises $ cd ~/Desktop/
>
>Topaz-Sue:Desktop $ pwd
>/Users/Topaz/Desktop

*Remember when you put quotes around a directory with spaces in it? You can do that with any command. For example, if you have a directory I Have Fun, then you can do: cd "I Have Fun"
>There seems to be two ways to accomplish changing directory location to a directory with spaces in the name. One way is to simply place "" around the directory name. Another way that the system file-completion TAB key showed me is to follow the closing quote with a backslash. Interesting.
>
>Topaz-Sue:another tmp $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_4/another tmp
>
>(master) Sue Uyetake
>Topaz-Sue:another tmp $ ls
>one A/  one BA/
>
>(master) Sue Uyetake
>Topaz-Sue:another tmp $ cd "one BA"/
>
>(master) Sue Uyetake
>Topaz-Sue:one BA $ cd ..
>
>(master) Sue Uyetake
>Topaz-Sue:another tmp $ cd "one BA"
>
>(master) Sue Uyetake
>Topaz-Sue:one BA $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_4/another tmp/one BA
>
>(master) Sue Uyetake

Chapter Five English Questions
======
1. Can you cd into the temp directory?
---
>To avoid changing your path into the root /tmp directory, you must type `cd ./tmp` or `cd tmp` ONLY  while sitting in the /workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5 directory.
>Either command will change your pointer to the tmp directory you created if your are sitting in the chapter_5 directory when you type it.

2. Why don't we go into the temp directory?
---
>Topaz-Sue:chapter_5 $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5
>
>(master) Sue Uyetake
>Topaz-Sue:chapter_5 $ cd tmp
>
>(master) Sue Uyetake
>Topaz-Sue:tmp $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5/tmp
>
>(master) Sue Uyetake
>Topaz-Sue:tmp $ ls
>stuff/
>
>(master) Sue Uyetake
>Topaz-Sue:tmp $ cd stuff/things/frank/joe/
>
>(master) Sue Uyetake
>Topaz-Sue:joe $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5/tmp/stuff/things/frank/joe
>
>(master) Sue Uyetake
>Topaz-Sue:joe $ cd ../../../../../tmp/
>
>(master) Sue Uyetake
>Topaz-Sue:tmp $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5/tmp
>
>(master) Sue Uyetake


3. Can you go to the slash temp directory?
---
>We can go to the root slash tmp directory when we explicitly name it as in `cd /tmp`
>
>Topaz-Sue:learn_command_line_exercises $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises
>
>(master) Sue Uyetake
>Topaz-Sue:learn_command_line_exercises $ cd /tmp
>
>
>Topaz-Sue:tmp $ pwd
>/tmp

4. Can you go to the slash temp slash log directory?
---
> If it exists, I can go to the slash tmp slash log directory by typing `cd /tmp/log`, but it does not exist so you will get an appropriate error message. Afterwards, I created it and encountered a little strangeness with the tmp linking to another place. All turned out well.
>
>Topaz-Sue:learn_command_line_exercises $ pwd
>/Users/Topaz/workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises
>
>(master) Sue Uyetake
>Topaz-Sue:learn_command_line_exercises $ cd /tmp/log/
>bash: cd: /tmp/log/: No such file or directory
>
>(master) Sue Uyetake
>
>Topaz-Sue:learn_command_line_exercises $ cd ./chapter_5/tmp/log
>
>bash: cd: ./chapter_5/tmp/log: No such file or directory
>
>(master) Sue Uyetake
>Topaz-Sue:learn_command_line_exercises $ mkdir ./chapter_5/tmp/log
>(master) Sue Uyetake
>
>Topaz-Sue:learn_command_line_exercises $ cd ./chapter_5/tmp/log

>Topaz-Sue:chapter_5 $ ls /tmp
>/tmp@
>
>(master) Sue Uyetake
>Topaz-Sue:chapter_5 $ mkdir /tmp/log
>
>(master) Sue Uyetake
>Topaz-Sue:chapter_5 $ ls /tmp
>/tmp@
>
>(master) Sue Uyetake
>Topaz-Sue:chapter_5 $ ls -l /tmp
>lrwxr-xr-x@ 1 root  wheel  11 Apr 14 14:06 /tmp@ -> private/tmp
>
>(master) Sue Uyetake
>Topaz-Sue:chapter_5 $ mkdir /tmp/log/
>mkdir: /tmp/log/: File exists
>
>(master) Sue Uyetake
>Topaz-Sue:chapter_5 $ ls -l /tmp/
>total 0
>prw-rw-rw-  1 Topaz  wheel    0 Sep 19 08:32 4EF1BD2D-53C0-4821-B62B-E40AB481E171_IN|
>prw-rw-rw-  1 Topaz  wheel    0 Sep 19 08:32 4EF1BD2D-53C0-4821-B62B-E40AB481E171_OUT|
>prw-rw-rw-  1 Topaz  wheel    0 Sep 14 17:39 EC2D9CB2-F3FC-48FE-A759-83711ACF1CE7_IN|
>prw-rw-rw-  1 Topaz  wheel    0 Sep 14 17:39 EC2D9CB2-F3FC-48FE-A759-83711ACF1CE7_OUT|
>drwx------  2 Topaz  wheel   68 Sep 28 07:17 KSDownloadAction.LjeVL11LcF/
>drwx------  3 Topaz  wheel  102 Sep 29 00:55 KSOutOfProcessFetcher.501.HVXI9pQwBk_bgiVJaTNhiQNhqxc=/
>drwx------  2 Topaz  wheel   68 Sep 28 07:17 KSOutOfProcessFetcher.501.I5ci1K_TwCwqo1sKvc0siaBbJTw=/
>drwx------  3 Topaz  wheel  102 Sep 12 02:03 com.apple.launchd.4RISk2rrVB/
>drwx------  3 Topaz  wheel  102 Sep 12 02:03 com.apple.launchd.d4ipcapn4g/
>drwxr-xr-x  2 Topaz  wheel   68 Sep 29 00:57 log/
>
>(master) Sue Uyetake


5. What does the .. argument to cd do? 
---
> The .. argument to cd will change location from the current directory to the directory above it. In our ./tmp/ example, if we type `cd ..` while in our created tmp directory, we will change location back upward to the chapter_5 directory.


