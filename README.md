# shell commands
---
##### pwd ; shows the current path in a hierarchical directory
---
##### cd ; change directory
---
##### ls ; list files and directories
```
$ ls_ list the files in the working directory
$ ls /bin_ list the files in the /bin directory ( or any other directory we care to specify )
$ ls -l_ list the files in the working directory in long format
$ ls -l /etc /bin_ list the files in the /bin directory and the /etc directory in long format
$ ls -la .._ list all files (even ones with names begginning with a period character, which are normally hidden) in the parent of the working directory in long format
```
---
##### cp ; copy files and directories
```
$ cp file1 file2_ copies the contents of file1 into file2. if file2 does not exist, it is created; otherwise, file2 is silently overwritten with the contents of file1.
$ cp -i file1 file2_ like above however, since the "-i" (interactive) option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.
$ cp file1 dir1_ copy the contents of file1(into a file named file1) inside of directory dir1.
$ cp -R dir1 dir2_ copy the contents of the directory dir1. If directory dir2 does not exist, it is created. Otherwise, it creates a directory named dir1 within directory dir2.
```
---
##### mv ; move files and directories or rename them.
```
$ mv file1 file2_ if file2 does not exist, then file1 is renamed file2. if file2 exists, its contents are silently replaced with the contents of file1.
$ mv -i file1 file2_ like above however, since the "-i"(interactive) option is specified, if file2 exists, the user is prompted before it is overwritten with the contents of file1.
$ mv file1 file2 dir1_ the files file1 and file2 are moved to diretory dir1, if dir1 does not exist, mv will exit with an error.
$ mv dir1 dir2_ if dir2 does not exist, then dir1 is renamed dir2. if dir2 exists, the directory dir1 is moved within directory dir2.
```
---
##### rm ; delete files and directories permantely and irreversevely
```
$ rm file1 file2_ delete file1 and file2.
$ rm -i file1 file2_ like above however, since the "-i"(interactive) option is specified, the user is prompted before each file is deleted.
$ rm -r dir1 dir2_ directories dir1 and dir2 are deleted along with all of their contents.
```
---
##### mkdir ; make a new directory

