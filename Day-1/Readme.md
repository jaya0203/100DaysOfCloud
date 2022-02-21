#Basic Linux Commands

**uname**\
To know which operating system logged on into

**whoami**\
To know who is user

**pwd**\
To know the print working directory

**ls**\
To display the contents of a directory

**ls -l**\
To display the contents of a directory in a list view

**ls -a**\
To display the contents of a directory in a list view, including hidden files

**cd**\
to change directory

**cd -**\
to know the last working directory or location

**cd ..**\
to get back to the parent directory of current directory

**cd /**\
to get back to root directory

**mkdir**\
to create a new directory

**VI EDITOR**
------------
* vi editor has different modes:-
    1. **insert mode** - where we can write content to our file\
      **i** - where cursor remains constant and gets into insert mode\
      **I** - where cursor moves beginning of the line and gets into insert mode\
      **a** - where cursor moves one character from existing position and gets into insert mode\
      **A** - where cursor moves down to the end of line from existing position and gets into insert mode\
      **o** - where cursor moves down one line from existing position and gets into insert mode\
      **O** - where cursor moves ahead one line from existing position and gets into insert mode
    2. **normal mode** 
       **:q** -quit the file
       **:w** -save the content of the file
       **:wq** -save the content and quit the file
       **:q!** -forcefully quit the file
       **:w!** -forcefully save the content of the file
 * creating empty file with vi editor **vi file_name**
 * copying the contents of file from one file to another file **cp source dest**
 * copying the contents of one directory to another directory **cp -r source dest**
 * removing the file **rm -i file_name**
 * removing the directory **rm -r direc_name**
 * renaming the file **mv old_file_name required_file_name**
 * moving the file from one location to another **mv src_path dest_path**

**USER MANAGEMENT**
------------------
* By default every linux machine is created with 'root' user
* user is an entity who will login into system
* types of users in linux:- \
  1.**Super user** - like root who holds all permissions to do any type of operation\
  2.**System user** - like apache, jenkins etc. typically associated with system applications like httpd, nginx etc.\
  3.**Normal user** - added manually by sysadmins by using useradd command.
* all users information is stored in /etc/passwd file
* every user created in linux will have a directory created in /home, with username
* creating a user by **adduser** command for eg: **adduser user1**
* creating a group by **groupadd** command for eg: **groupadd group1**
* adding user to the group by **usermod -g group_name user_name**

**PERMISSIONS**
-------------
r- read -4
w- write -2
x- execute -1
u- owner
g- group
o- other
* to change ownership of file **chmod** eg: chmod o+w file_name
* to change only file owner **chown uname file**
* to change only group owner **chgrp uname file**

**PACKAGES INSTALLATION**
-----------------------
* for installing package **sudo yum -y install package_name**







