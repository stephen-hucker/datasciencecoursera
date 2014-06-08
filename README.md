datasciencecoursera
===================

Test repo for the Coursera course: The Data Scientist’s Toolbox - June 2014

Created using the commands shown in the video "05_Creating_a_Github_Repository.mp4"

Repo created on a Macintosh running OS X 10.9

```
Sun Jun 08 ~ 
[14] 22:17:35--> cd git

Sun Jun 08 ~/git 
[15] 22:17:39--> ls

Sun Jun 08 ~/git 
[16] 22:17:40--> mkdir datasciencecoursera

Sun Jun 08 ~/git 
[17] 22:18:05--> cd datasciencecoursera

Sun Jun 08 ~/git/datasciencecoursera 
[18] 22:18:10--> git init
Initialized empty Git repository in /Users/stephen/git/datasciencecoursera/.git/

Sun Jun 08 ~/git/datasciencecoursera 
[19] 22:18:46--> git remote add origin https://github.com/stephen-hucker/datasciencecoursera.git

Sun Jun 08 ~/git/datasciencecoursera 
[21] 22:22:17--> ls -la
total 0
drwxr-xr-x  3 admin  staff  102  8 Jun 22:18 .
drwxr-xr-x  4 admin  staff  136  8 Jun 22:18 ..
drwxr-xr-x  9 admin  staff  306  8 Jun 22:19 .git
```

R is installed!

```
Sun Jun 08 ~/git/datasciencecoursera 
[51] 22:37:23--> r

R version 3.1.0 (2014-04-10) -- "Spring Dance"
Copyright (C) 2014 The R Foundation for Statistical Computing
Platform: x86_64-apple-darwin13.1.0 (64-bit)

R is free software and comes with ABSOLUTELY NO WARRANTY.
You are welcome to redistribute it under certain conditions.
Type 'license()' or 'licence()' for distribution details.

  Natural language support but running in an English locale

R is a collaborative project with many contributors.
Type 'contributors()' for more information and
'citation()' on how to cite R or R packages in publications.

Type 'demo()' for some demos, 'help()' for on-line help, or
'help.start()' for an HTML browser interface to help.
Type 'q()' to quit R.

> 
Save workspace image? [y/n/c]: n
```

Created HelloWorld.md and 'pushed' it to git

```
[70] 01:42:36--> git push
warning: push.default is unset; its implicit value is changing in
Git 2.0 from 'matching' to 'simple'. To squelch this message
and maintain the current behavior after the default changes, use:

  git config --global push.default matching

To squelch this message and adopt the new behavior now, use:

  git config --global push.default simple

See 'git help config' and search for 'push.default' for further information.
(the 'simple' mode was introduced in Git 1.7.11. Use the similar mode
'current' instead of 'simple' if you sometimes use older versions of Git)

Username for 'https://github.com': stephen-hucker
Password for 'https://stephen-hucker@github.com': 
Everything up-to-date
```
Local repo on my Mac:

```
Mon Jun 09 ~/git/datasciencecoursera 
[73] 01:46:23--> ls -la
total 16
drwxr-xr-x   5 admin  staff  170  9 Jun 01:31 .
drwxr-xr-x   7 admin  staff  238  8 Jun 23:18 ..
drwxr-xr-x  13 admin  staff  442  9 Jun 01:37 .git
-rw-r--r--   1 admin  staff   27  9 Jun 01:31 HelloWorld.md
-rw-r--r--   1 admin  staff  956  8 Jun 23:18 README.md

Mon Jun 09 ~/git/datasciencecoursera 
[74] 01:46:33--> cat HelloWorld.md 
## This is a markdown file
```
