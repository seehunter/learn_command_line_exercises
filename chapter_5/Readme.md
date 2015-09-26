Chapter Five Do More
======
*cd to the joe directory with one command.
*cd back to temp with one command, but not further above that.
*Find out how to cd to your "home directory" with one command.
*cd to your Documents directory, then find it with your GUI file browser (Finder, Windows Explorer, etc.).
*cd to your Downloads directory, then find it with your file browser.
*Find another directory with your file browser, then cd to it.
Remember when you put quotes around a directory with spaces in it? You can do that with any command. For example, if you have a directory I Have Fun, then you can do: cd "I Have Fun"


Chapter Five English Questions
======
1. Can you cd into the temp directory?
---
>To avoid changing your path into the root /tmp directory, you must type `cd ./tmp` while sitting in the /workspace/davinci_coders_t3_2015/homework/learn_command_line_exercises/chapter_5 directory.
>Alternatively, you may type `cd tmp`
>Either command will change your pointer to the tmp directory you created if your are sitting in the chapter_5 directory when you type it.

2. Why don't we go into the temp directory?
---
>We don't go into the root tmp directory because we did not name the absolute directory path specification "/tmp".

3. Can you go to the slash temp directory?
---
>We can go to the slash tmp directory when we explicitly name it as in `cd /tmp`

4. Can you go to the slash temp slash log directory?
---
> I can go to the slash tmp slash log directory by typing `cd /tmp/log`

5. What does the .. argument to cd do? 
---
> The .. argument to cd will change location from the current directory to the directory above it. In our ./tmp/ example, if we type `cd ..` while in our created tmp directory, we will change location back upward to the chapter_5 directory.


