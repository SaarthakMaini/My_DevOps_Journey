# Linux

## What happens when you start a computer?

- Executes the softwares that are there in the BIOS(Basic Input Output System)
- BIOS is also known as Firmware
- It comes by default in a computer stored in a small chip in the motherboard
- This small chip is a ROM(Read Only Memory)
- It's job is to check if the system is working correctly or not
- It will check if the :
    - Memory is loaded
    - RAM(Random Access Memory) is connected
    - What devices are connected to the computer
    - Connection to Keyboard and Mouse
    - What drives are there
- Basically, it checks to see if the Operating System is ready to launch
- Then it loads the Boot Loader which is responsible for initializing the Operating System

## What is an Operating System?

An Operating System is a software to manage and operate a computing device(Mobile,Desktop,Tablet,etc.)

## Conditions For A Software To Be Considered As An Operating System

- Kernel
- File System
- User Interface [CLI or GUI]
- It should be able to take our commands/instructions and it should be able to manipulate the data in the memory based on that

## What is a File System?

A File System is a method or data structure that the Operating System uses to store and retrieve data in the memory.

## What is a Kernel?

It is the core of the Operating System. It generally has complete control over the system. It can control the memory, the CPU, and facilitates the interaction of the software with the hardware, and it is because of this reason that the Kernel has complete control over the system.

## Why use Linux?

- It is Open Source
- Supports almost all programming languages
- Terminal
- Easier to get tasks done via Bash Scripting
- Ability to ssh into a server which you might have hosted remotely

## History Of Linux

In 1969, Dennis Ritchie and Ken Thompson came up with the UNIX Operating System. They later rewrote it in C language to make the Operating System more portable. It soon became widely used.

A decade later, Richard Stallman started working on the GNU project. At that time many other Operating Systems were created such as BSD, MINIX, etc. which were UNIX like but they lacked a common unified Kernel for all these versions of different Operating Systems.

In 1991, Linus Trovald created the Linux Kernel which acted as a unified kernel for all the distributions of Linux.

## Terminal/Console

It is a text input and output environment. It's job is to launch the shell.

**NOTE:** 

- A shortcut to open the terminal in Linux : `Ctrl + Alt + T`

## Shell

Shell is a command line interpreter which executes each command line by line.

## Linux Commands

`cd` : It stands for "Change Directory". It is used to switch between directories.

**NOTE:**

1. Current Directory : .
2. Parent Directory : ..
3. Home Directory : ~
4. Previous Directory : -

`ls` : It is used to list down all the sub-directories and files in the specified directory. <br>
`ls -a` : It is used to list down all the sub-directories and files `including hidden items` in the specified directory. <br>
`ls -l` : It is used to list down all the sub-directories and files in the specified directory `in a detailed manner`. <br>
`mkdir` : This command is used to make a new directory. <br>
`clear` : This command is used to clear the terminal. <br>
`file name_of_file` : This command shows the details about the file specified. <br>
`cat` : Displays the file's contents. It can also be used to combine the the contents of multiple files and output it to the terminal. <br>
`rm` : It is used to remove a file. <br>
`rmdir` : This command is used to remove the directory.It cannot remove a directory if it is empty.<br>
`rm -rfv` : This command is an extension of the rm command. It includes the flags r,f and v. Here, "r" stands for recursive , "f" stands for force and "v" stands for verbose. This command is used to delete a non-empty directory. <br>
`cp old_path/name_of_file new_path` : This command is used to copy files and directories from one place to another in the file system. <br>
`mv old_path/name new_path/new_name` : This command is used to move files and directories from one place to another in the file system. It can also be used to rename a pre-existing file. <br>
`man` : This command is used to show the manual pages of the commands. <br>
`whatis` : Describes the command in short. <br>

**NOTE:** # is used to add comments.


