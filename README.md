# Bash Cheatsheet

## Introduction
The Bash Cheatsheet repository is a place where you can view a cheatsheet for bash, a command-line interface language that is regularly used in stuff like Linux or maybe Git Bash. You can also find useful pieces of information here (especially for beginners) and learning resources which are related to bash in one way or another. This repository is a mini-project for a much bigger project called the [*Learning-Hub Project*](https://github.com/ItemHunt/Learning-Hub). 

## How to Contribute
I welcome any contributors to this mini-project. Feel free to fork the project and add/edit stuff here and send out a pull request for review. If all is good, I should approve the pull request. In case you are new to GitHub, refer to [CONTRIBUTING](CONTRIBUTING.md) for a more detailed guide.

## Contributors
<a href="https://github.com/ItemHunt/Bash-Cheatsheet/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ItemHunt/Bash-Cheatsheet" />
</a>

<!-- Contributors section made with [contrib.rocks](https://contrib.rocks). -->

## Table of Contents
### General bash
- [Essentials](https://github.com/ItemHunt/Bash-Cheatsheet#essentials)
- [Search & Navigation](https://github.com/ItemHunt/Bash-Cheatsheet#search--navigation)
- [System Details & Modification](https://github.com/ItemHunt/Bash-Cheatsheet#system-details--modification)
- [Directory or File Use/Modification/Deletion/Creation](https://github.com/ItemHunt/Bash-Cheatsheet#directory-or-file-usemodificationdeletioncreation)
- [Networking & Servers](https://github.com/ItemHunt/Bash-Cheatsheet#networking--servers)
- [Package Management](https://github.com/ItemHunt/Bash-Cheatsheet#package-management)
- [Process Management](https://github.com/ItemHunt/Bash-Cheatsheet#process-management)
- [Others](https://github.com/ItemHunt/Bash-Cheatsheet#others)

### Git Bash
- [General Commands](https://github.com/ItemHunt/Bash-Cheatsheet#networking--servers)
- [Git Branches](https://github.com/ItemHunt/Bash-Cheatsheet#git-branches)
- [User-Setting Modification](https://github.com/ItemHunt/Bash-Cheatsheet#user-setting-modification)
- [Others](https://github.com/ItemHunt/Bash-Cheatsheet#others-1)

### Bash Shortcut Keys and Symbols
- [Symbols](https://github.com/ItemHunt/Bash-Cheatsheet#symbols)
- [Bash Shortcuts](https://github.com/ItemHunt/Bash-Cheatsheet#bash-shortcuts)

### Additional Information & Learning Resources
- [Additional Information For Bash](https://github.com/ItemHunt/Bash-Cheatsheet#additional-information-for-bash)
- [Learning Resources List](https://github.com/ItemHunt/Bash-Cheatsheet#learning-resources-list)

## Cheatsheet
### General Bash
#### Essentials
- **``$ man '(tool)'`` -** opens an extensive help menu for the specified command
- **$ '(tool)' -h/help -** opens a brief help menu for the specified command
- **$ apropos '(keyword)' -** searches for terminal commands that correlate to the specified keyword
- **$ sudo -** allows you to execute a command with admin rights
- **$ clear -** clears everything on the terminal
- **$ help -** shows the help menu

#### Search & Navigation
- **$ pwd -** print working directory
- **$ ls -** list all items in working directory
- **$ cd '(working directory, you can use “..” to go back once)' -** change working directory
- **$ locate -** uses the locale database to search for things on the system
- **$ which -** provides the path to a specificed file or link
- **$ find -** searches for files in a directory hierarchy
- **$ grep -** searches for specific results that have given patterns

#### System Details & Modification
- **$ whoami -** tells you what user you are logged in as
- **$ id -** Gives user identity
- **$ hostname -** tells you the name of the current host system
- **$ uname -** tells you the operating system name
- **$ addgroup -** adds a group to the system
- **$ delgroup -** deletes a group from the system
- **$ useradd -** creates a user
- **$ usermod -** modifies a user account
- **$ passwd -** changes the password of a user
- **$ su -** used to switch users
- **$ lsblk -** Lists block devices
- **$ lsusb -** lists USB devices
- **$ lsof -** lists opened files
- **$ lspci -** lists PCI devices

#### Directory or File Use/Modification/Deletion/Creation
- **$ mkdir '(name of new directory)' -** creates a directory inside the current branch of the repository
- **$ rmdir '(name of target directory)' -** removes a target directory
- **$ rm '(name of file  + format)' -** removes a target file
- **$ cat '(file name with format)' -** prints the contents of the file into the terminal
- **$ mv -** used to move or rename files
- **$ cp -** used to copy files or directories
- **$ touch '(file name and format)' -** allows you to create a file of your choice

#### Networking & Servers
- **$ ifconfig -** Used to deal with the network interface
- **$ ip -** used to deal with your networking
- **$ netstat -** shows network status
- **$ curl -** utility used to transfer data from or to a server
- **$ wget -** can be used instead of 'curl' to get files from FTP or HTTP server
- **$ python3 -m http.server -** used to start a Python3 web server on TCP port 8000

#### Package Management
- **$ dpkg -** low-level package manager used to install, remove, or configure Debian-based packages
- **$ apt -** high-level package manager
- **$ aptitude -** another high-level package manager that can be used as an alternative to apt
- **$ snap -** used to install, remove, and configure snap packages
- **$ gem -** standard package manager for Ruby
- **$ pip -** standard package manager for Python

#### Process Management
- **$ systemctl -** used to manage processes and daemons
- **$ ps -** outputs current processes
- **$ journalctl -** shows process journal
- **$ kill -** used to send a kill signal to a process
- **$ bg -** puts a process into background
- **$ jobs -** outputs a list of all processes running in the background
- **$ fg -** places a process into the foreground

#### Others
- **$ ss -** used to investigate sockets
- **$ who -** shows who is currently logged in
- **$ env -** prints the environtment or sets and then runs a commands
- **$ tree -** command to list the things inside of a directory recursively
- **$ nano -** used to open and use Nano, a terminal based text editor that is easier to use than Vim
- **$ vim -** used to open and use Vim, a terminal based text editor that can do a lot of stuff but is difficult to use
- **$ updatedb -** updates the locale database for existing contents on the system
- **$ more -** pager used to read STDOUT or files
- **$ less -** upgraded version of the more command
- **$ head -** prints the first ten lines of STDOUT or a file
- **$ tail -** prints the last ten lines of STDOUT or a file
- **$ sort -** sorts the contents of a file or STDOUT
- **$ cut -** removes sections from each line of files
- **$ tr -** replaces certain characters
- **$ column -** utility that format its input into multiple columns
- **$ awk -** pattern scanning and processing language
- **$ sed -** a stream editor for the transformation and filtering of text
- **$ wc -** prints newline, word, and byte counts for a provided input
- **$ chmod -** changes the permissions of a file or directory
- **$ chown -** changes the owner and group of a file or directory


### Git Bash
#### General Commands
- **$ git -** version control system utility
- **$ git status -** shows you the status of your Git repository (what is staged, unstaged, new, and what was modified recently)
- **$ git add '(“.” for all or specify what file you are staging)' -** stages file/s
- **$ git init -** initializes or activates or converts the current working directory into a git repository
- **$ git commit -m '(insert commit comment)' -** shortcut for committing files/changes and adding a comment without going into your text editor (e.g. Vim, Nano)
- **$ git push -u origin '(Name of the main branch of the remote repository)' -** pushes all contents of the master branch into the remote repository your local repository is connected to. This allows your remote repository files to be updated or to increase/decrease in number
- **$ git pull -** pulls all files/changes made on the remote repository into your local repository
- **$ git remote add origin '(insert the link github provides you for this specific command)' -** allows you to connect your local repository into a remote repository (or online repository)

#### Git Branches
- **$ git branch '(branch name)' -** helps you create a new independent branch on your local repository
- **$ git merge '(branch name)' -** Allows you to merge a branch into the master branch
- **$ git checkout '(branch name)' -** switches your git repository branch to the specified branch

#### User Setting Modification
- **$ git config –global core.editor '(insert editor you want eg. vim, nano, etc)' -** helps you change your text editor
- **$ git rm –cached '(name of file with format)' -** unstages a specified file
- **$ git config –global user.email ‘(insert your email)’ -** allows you to set your Git email
- **$ git config –global user.name '(insert username)' -** allows you to set your Git name

#### Others
- **$ git clone '(http, ssh, or url link)' -** allows you to clone an existing repository into your system
- **$ git remote -** shows you if your local repository is connected to a remote repository (or online repository)
- **$ ssh-keygen -t rsa -C '(insert your Github Email)' -** allows you to generate a ssh key that you can connect to your github. This allows you to have a secure way of interacting with your remote repository using your local repository
- **$ git log -** shows you all previous saved changes


### Bash Shortcut Keys and Symbols
#### Symbols
- **&& -** stands for 'and' in programming. You can use this to trigger multiple different commands in the same time
- **|| -** stands for 'or' in programming. You can use this to trigger commands based off conditions. For example, if the first command does not work, the second will run instead

#### Bash Shortcuts
- **arrow up/down** key on the bash terminal allows you to check and navigate previously used commands
- **ctrl + l** when in the bash terminal is the shortcut way to clearing your terminal screen
- **q** when in the bash terminal allows you to exit whatever your stuck to (like a log or something) and return to the position where you can execute commands
- **ctrl + a** moves your cursor to the beginning of the line
- **ctrl + e** moves the cursor to the end of the line
- **ctrl + <- or ->** lets you move quickly in either the left or right direction, useful if you typed something long and you want to fix something in-between
- **alt + b or f** allows you to jump backward or forward
- **tab** initiates auto complete
- **ctrl y** allows you to paste the erased text or word
- **ctrl + c** allows you to end the current task or process by sending a SIGINT
- **ctrl + z** converts a current process into a background one via SIGTSTP signal
- **ctrl + r** lets you check command history
- **alt and tab** helps you switch between opened applications
- **ctrl +** lets you zoom in
- **ctrl -** lets you zoom out
- **ctrl + u -** erases everything from the current spot of the cursor to the beginning of the line
- **ctrl + k -** erases everything from the current spot of the cursor to the end of the line
- **ctrl + w -** erases the word preceding the cursor position
- **ctrl + d -** closes STDIN pipe, also known as End-Of-File (EOF) or End-of-Transmission
- **ctrl + z -** closes the current process by sending a SIGTSTP signal
- **Alt + Tab -** siwtch between opened applications

## Additional Information For Bash

### Additional Information for Git Bash
- **.gitignore** is a file that allows you to have Git ignore specific files or folders in your local repository. To use it, simply put the file name or folder that you want to be ignored. If you have a text file called "Text.txt" just type its name inside .gitignore to have Git ignore that specific file

## Learning Resources List

### Bash 
- Linux Fundamentals (video) https://www.youtube.com/playlist?list=PLIhvC56v63IJIujb5cyE13oLuyORZpdkL
- HTB Academy Linux Fundamentals (website) https://academy.hackthebox.com/module/details/18

### Git Bash
- Git Documentation Link (website) https://git-scm.com/doc
- GitHub Documentation Link (website) https://docs.github.com/en
- Easy To Understand Beginner Guide to Git (video) https://www.youtube.com/watch?v=SWYqp7iY_Tc
- Git Crash Course (video) https://www.youtube.com/watch?v=RGOj5yH7evk&t
