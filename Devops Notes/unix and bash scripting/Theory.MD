#### 1. What does an operating system do?

   - Manage memory allocation for running applications
   - Process scheduling; managing CPU (central processing unit) allocation for running processes
   - Manage data storage
   - File management
   - Manage Input/Output (I/O), specifically process input from devices such as keyboards and touchpads, send output to a display
   - Manage peripherals such as printers and scanners

#### 2. Unix is a multi-user operating system. Under Unix, each user can access and share system resources such as memory. In contrast, other operating systems, like Windows, start a new session with distinct resources for each user.

#### 3. The portion of the operating system that handles the computer resources (CPU, RAM and devices) is referred to as the kernel. The initial version of the Linux kernel, created by Linus Torvalds, was written specifically for the Intel 80386 chip, a standard chip used in personal computers in the late 1980’s and 1990’s. The kernel has been ported to many different chip architectures since then.

There is also a set of standard software utilities that accompany the system that provide services such as a command line interpreters, file utilities and editors that we will cover in this module. Many of the Linux tools are written in C and are therefore machine independent.
	
Tux, the Linux mascot
Tux, the Linux mascot
When people refer to the Linux operating system they mean the kernel as well as the accompanying set of tools and libraries that is actually called GNU. Some people refer to this combination as GNU/Linux (as you see in the message of the day) but we will just refer to the kernel plus the utilities as Linux. For the most part the utilities that are packaged with Linux are functionally equivalent to the utilities with the same name in UNIX, but they have been rewritten.



#### 4. The Command Line Interface
The Command Line Interface, better known as CLI, or Shell is one way to interact with your computer. The command line interface which you see in the terminal window on the left is called Bash. It is the default login shell for most Linux distributions. It is considered very portable and is widely used on many UNIX implementations as well as on other operating systems.
Command Line Prompt
In the terminal window on the left you will see the command line prompt. It looks something like what you see below:

codio@matrixrudolf-trustgame:~/workspace$

Take a look at the different pieces of the command prompt:

    The first part of the command prompt is the username followed by the @ symbol. On the Ubuntu server you see in the terminal, Codio has automatically created a user called codio.
    The server address after the @ sign is specified using a unique combination of words. Codio runs each assignment/lesson as a distinct Ubuntu so you will notice that the server address changes throughout this course.
    The information after the colon is an abbreviation of the current working directory.
    The command line prompt ends with a $
    
    
![image](https://user-images.githubusercontent.com/96974600/196700159-100ded28-f3e3-4d10-8b61-7c3901f59b32.png)


#### 4. ```cat``` is the shell command - it is short for “catalog” and it prints out the contents of a file.
In the terminal window on the left type:

```cat /etc/os-release```

/etc/os-release is the file we are printing out. In a directory called etc there is information about the release we are using, in a file called os-release.
You should see something like this:

```
NAME="Ubuntu"
VERSION="18.04.6 LTS (Bionic Beaver)"
ID=ubuntu
ID_LIKE=debian
PRETTY_NAME="Ubuntu 18.04.6 LTS"
VERSION_ID="18.04"
HOME_URL="https://www.ubuntu.com/"
SUPPORT_URL="https://help.ubuntu.com/"
BUG_REPORT_URL="https://bugs.launchpad.net/ubuntu/"
PRIVACY_POLICY_URL="https://www.ubuntu.com/legal/terms-and-policies/privacy-policy"
VERSION_CODENAME=bionic
UBUNTU_CODENAME=bionic
```

### 5. Listing directories

>** Note**
>Dots in bash are useful utilities that help with navigating the file system using the CLI.





