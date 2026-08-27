# Bandit Level 1

## Objective

Connect to the Bandit server and retrieve the password for the next level. This level introduces remote access using SSH and familiarizes you with navigating a Linux environment. After logging in successfully, I explored the current directory using `ls` and viewed the required file using the `cat` command. This level served as my introduction to OverTheWire Bandit and reinforced the basics of remote authentication and file reading in Linux.

#### Password

`6y2kwnwK6#######2T1cpFEKOhNR`

---

# Bandit Level 2

## Objective

Using the password obtained from the previous level, I logged into the next Bandit account. I listed the available files using `ls` and identified the file containing the next password. By reading the file with the `cat` command, I successfully retrieved the credentials for the following level. This challenge reinforced the importance of basic Linux navigation and reading file contents from the command line.

#### Password

`PK8fYLZg2h########L1iEPKdD3QToB`

---

# Bandit Level 3

## Objective

This level introduced working with filenames that contain spaces. After listing the directory contents, I learned that normal commands fail when spaces are interpreted as separate arguments. I solved the challenge by correctly referencing the filename using quotation marks or escaped spaces before reading it with `cat`. This level strengthened my understanding of handling special filenames within Linux.

#### Password

`7ZZ2LFryk#######clcL7tGYJPME`

---

# Bandit Level 4

## Objective

In this level, I explored the use of `ls -la` to display hidden files and directories. Linux stores many configuration files as hidden entries beginning with a dot (`.`). By listing all files and navigating appropriately with `cd`, I located the hidden file containing the next password. This exercise demonstrated the importance of hidden files in Linux systems and introduced a commonly used command for system administration.

#### Password

`<Password for Level 5>`

---

# Bandit Level 5

## Objective

This level built upon the previous challenges by combining directory navigation with file discovery techniques. I used commands such as `cd`, `ls`, and `ls -la` to inspect the directory structure and locate the required file before reading its contents with `cat`. The challenge emphasized careful observation and reinforced the fundamental Linux commands that are essential for system administration and cybersecurity tasks.

#### Password

`<Password for Level 6>`