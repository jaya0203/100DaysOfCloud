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
  1. insert mode- where we can write content to our file
      **i** - where cursor remains constant and gets into insert mode
      **I** - where cursor moves beginning of the line and gets into insert mode
      **a** - where cursor moves one character from existing position and gets into insert mode
      **A** - where cursor moves down to the end of line from existing position and gets into insert mode
      **o** - where cursor moves down one line from existing position and gets into insert mode
      **O** - where cursor moves ahead one line from existing position and gets into insert mode
  3.normal mode 

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





