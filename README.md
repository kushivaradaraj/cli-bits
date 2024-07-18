# cli-bits

## **Reading Objectives**

In this reading, you will gain an understanding of the basics of the Linux operating system. This reading will discuss the core component of the Linux operating system, called the Linux kernel, and its various key features. It will also discuss the background processing in Linux and how Unix and Linux share a strong historical connection. This reading will list the well-known Linux distributions and the common package managers. This reading will also list the advantages of Linux and the multi-user support that it offers.

## **Introduction to the Linux Operating System**

Linux is a powerful and versatile operating system that was developed by Linus Torvalds in 1991. It offers a wide range of features and capabilities that make it a popular choice for various environments, including servers, desktops, smartphones, and IoT devices. Let us explore some key aspects of Linux and its historical connection with Unix.

## **Key Features of Linux**

Operating System (Kernel): The core of the Linux operating system is called the kernel, which manages various hardware and software resources.

_**Command Line Interface:**_ Linux provides a command line interface (CLI) that allows users to interact with the system using text-based commands, offering powerful control and flexibility.

_**Open Source:**_ Linux is an open-source operating system, meaning its source code is freely available for anyone to view, modify, and distribute.

_**Hierarchical File System:**_ Linux uses a hierarchical file system, where directories (folders) and files are organized in a tree-like structure.

_**Supports Multiple Users:**_ Linux supports multiple users to share a single computer system simultaneously, making it suitable for multi-user environments.

_**Stable:**_ Linux is known for its stability and reliability, making it a preferred choice for critical systems and applications.

_**Diverse Environments:**_ Linux is versatile and finds application in various environments, including servers, desktops, smartphones, and IoT devices.

_**Wide Range of Programming Languages:**_ Linux supports a vast array of programming languages, making it an excellent platform for software development.

## **Linux Kernel**

The Linux kernel is the core component of the Linux operating system. It serves as the bridge between hardware and software, managing system resources and enabling various applications to interact with the computer's hardware. The Linux kernel is open source, allowing developers worldwide to contribute to its continuous improvement.

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/3a7a06b7-a216-477b-bd4e-71c60d86f018image1.jpeg?expiry=1721433600000&hmac=LBaErvEqG1-6qjeapCkzgiJrGT9GFc-2ck01I54ZOAk)

**Source**: [http://nathanielgmartin.com/unix/Wk01/r1-intro.html](http://nathanielgmartin.com/unix/Wk01/r1-intro.html)

## **Key features of the Linux kernel include:**

_**Resource Management:**_ The kernel allocates and manages resources like CPU, memory, and peripherals, ensuring efficient utilization and fair distribution among processes.

_**Device Drivers:**_ It provides device drivers to facilitate communication between hardware components and software applications, enabling seamless access to peripherals.

_**Process Management:**_ The kernel oversees the creation, execution, and termination of processes, allowing multitasking and proper sharing of CPU time.

_**Memory Management:**_ It organizes and optimizes the system's memory, handling virtual memory, page allocation, and memory protection.

_**Inter-Process Communication (IPC):**_ The kernel facilitates communication between different processes, allowing them to exchange data and collaborate.

_**Security:**_ The kernel enforces security measures, controlling user access rights, protecting system resources, and ensuring data integrity.

_**File System Support:**_ It supports various file systems, enabling data storage, retrieval, and organization.

_**Networking:**_ The kernel includes networking protocols and drivers, allowing network connectivity and communication.

## **Background Processing in Linux**

In Linux, background processing refers to the execution of tasks or commands that run independently of the active terminal or user session. These processes are detached from the terminal and continue running even if the user logs out or closes the terminal window.

There are several ways to run commands in the background in Linux:

_**Using the & symbol:**_ To run a command in the background, simply append an ampersand (&) at the end of the command. For example:

$ command &

_**Using nohup:**_ The nohup command allows running a command immune to hangups (i.e., it keeps running even if the user logs out). It is often used for long-running processes that need to continue running independently. Example:

$ nohup command &

Background processing is commonly used for tasks like system updates, file transfers, backups, data processing, and software compilations.

## **Unix and Linux Historical Connection**

Unix and Linux share a strong historical connection, with Linux being influenced by Unix's design principles. Linux's open-source nature, extensive community support, and compatibility with Unix have made it a dominant force in modern computing, serving a wide range of users and devices across the globe.

Unix was developed in the late 1960s at Bell Labs by Ken Thompson, Dennis Ritchie, and others. It became the foundation for many commercial Unix variants, such as Solaris, AIX, and HP-UX.

Both Unix and Linux share a similar design philosophy of simplicity, modularity, and the use of small, specialized tools to perform tasks. Both Unix and Linux offer powerful CLIs with similar commands and utilities, allowing users to interact with the system efficiently.

Unix and Linux both follow a hierarchical file system structure, with directories organized in a tree-like format, starting from the root directory.

## **Popular Linux Distributions**

Linux serves as the foundation for numerous distributions, each tailored to specific needs and preferences. Some well-known Linux distributions include:

-   Ubuntu
    
-   Rocky Linux
    
-   Red Hat Enterprise Linux
    
-   Debian
    
-   Kali
    
-   SUSE Linux
    
-   Arch Linux
    
-   Raspbian
    
-   MX Linux
    
-   Fedora
    

## **Package Management**

Linux distributions use package managers to install, update, and remove software packages. Two common package managers are:

_**APT (Advanced Package Tool):**_ primarily used in Debian-based distributions like Ubuntu and Linux Mint. It uses .deb packages.

_**yum (Yellowdog Updater, Modified):**_ used in Red Hat–based distributions such as Red Hat Enterprise Linux (RHEL), CentOS, and Fedora.

## **Linux Command Line Interface (CLI)**

The Linux terminal provides a command line interface (CLI) that allows users to perform various tasks, manage files, and processes efficiently. Different shells, such as C Shell, Bourne Shell, and Korn Shell, interpret and execute commands.

## **Advantages of Linux**

_**Vast Array of Development Tools:**_ Linux provides an extensive collection of development tools and programming languages for software development.

_**Automation with Shell Scripting:**_ Developers can automate repetitive tasks using shell scripting in the Linux CLI.

_**Cost-Effective:**_ Linux is freely available, making it an attractive option for individual developers and startups.

## **Multi-User Support**

One of the key strengths of Linux is its robust multi-user support, which allows multiple users to access and utilize the same system simultaneously. This feature is essential in shared environments, such as servers, educational institutions, and workplaces, where multiple users need to interact with the system concurrently. The following are the main aspects of Linux’s multi-user feature:

1.  **User accounts:** Each user on a Linux system has a unique user account. A user account is associated with a username and a unique user ID (UID). The system uses the UID internally to differentiate between users.
    
2.  **User privileges:** Linux differentiates users based on their privileges. The root user (superuser) has administrative access and can perform system-wide changes. Regular users have limited access and can only modify files and settings they are permitted to.
    
3.  **User authentication:** When users log in, they need to provide a valid username and password for authentication. The system verifies the credentials against the user account database to grant access.
    
4.  **Concurrent sessions:** Linux allows multiple users to log in and run processes simultaneously. Each user gets their own session, and their processes are isolated from other users’ processes for security and privacy.
    
5.  **Process isolation:** Processes run by different users are isolated from each other, preventing unauthorized access to each other’s data and resources. This isolation is crucial for system stability and security.
    
6.  **File permissions:** Linux uses file permissions to control access to files and directories. Each file and directory has permission settings that determine which users can read, write, or execute them.
    
7.  **Home directories:** Each user typically has a home directory where they can store their files and personal settings. Home directories are usually named after the users’ usernames (e.g., /home/username).
    
8.  **Superuser (root) privileges:** The root user has unrestricted access to the entire system. Root privileges are required to perform critical system-level tasks, such as installing software, modifying system configurations, and managing user accounts.
    
9.  **su and sudo commands**_**:**_ The su (switch user) and sudo (superuser do) commands allow users to switch to another user’s account or execute specific commands with root privileges, respectively. This provides a controlled and audited way to perform administrative tasks. Linux’s multi-user feature is fundamental to its versatility and popularity as a server operating system.
    

## **Reading Summary**

In this reading, you have learned the following:

-   How the Linux operating systems offer a rich set of features, flexibility, and stability, making them a popular choice for a wide range of applications and environments.
    
-   How Linux provides the tools and capabilities to meet the needs effectively for a developer, system administrator, or enthusiast.
    
-   How one explores and experiments with various Linux distributions to find the one that best suits one’s requirements.





## **Reading Objective:**

In this reading, you will gain an understanding of the life cycle of a user session in Linux. This reading also focuses on some essential Linux commands and their usage through examples.

## **1\. Logging into Linux System**

## **Life Cycle of a User Session in Linux**

In a Linux environment, a user session goes through a sequence of steps from login to logout. Here's an overview of the process:

_**Login Attempt Initiation:**_

A user initiates a login attempt either through a graphical login manager or a text-based terminal.

For remote connections, users can log in via SSH (Secure Shell).

_**Username and Password Entry:**_

Users enter their username and password during the login attempt.

The system uses this information to authenticate the user's identity.

_**Authentication:**_

The system compares the entered password with the encrypted password stored in the system's user account database (usually in the /etc/shadow file).

If the authentication is successful, the user gains access to the system.

_**Session Initialization:**_

Upon successful authentication, the system initializes the user's session.

This involves setting up the user's environment, loading necessary configurations, and executing startup scripts.

_**Assigning a Shell:**_

After session initialization, the system assigns the user a shell (C Shell, Bourne Shell, Bourne Again Shell – BASH, Korn Shell, etc.), which is a command-line interpreter.

The default shell in most Linux distributions is Bash (Bourne Again SHell).

_**Session Start:**_

With the session initialized and the shell assigned, the user can start using the system.

In a graphical environment, this means accessing the desktop environment.

In a text-based environment, the user gains access to the shell.

_**Logging Out:**_

When the user finishes their tasks, they can log out to end the session.

Logging out involves cleaning up processes or resources associated with the session.

## **2\. Manual Help & Linux Basic Linux Commands**

Here are some essential Linux commands and their usage:

_**Command: passwd**_

The passwd command in Linux is used to change a user's password. It allows users to set a new password for their account or, if you have administrative privileges, change the password for another user. The passwd command can be run from the terminal.

**Syntax:**

passwd \[options\] \[username\]

**Options:**

\-l: Lock the password of the specified account.

\-u: Unlock the password of the specified account.

\-d: Delete the password of the specified account.

\-e: Expire the password of the specified account.

**Example 1: Changing Your Own Password:**

Suppose you are logged in as a regular user "john" and want to change your own password. You can run the passwd command without specifying a username:

$ passwd

Changing password for john.

(current) UNIX password: \[enter your current password\]

New password: \[enter your new password\]

Retype new password: \[retype your new password\]

passwd: password updated successfully

**Example 2: Changing Another User's Password (Requires Admin Privileges):**

If you have administrative privileges (e.g., you are the root user or a user with sudo access), you can change the password of another user. In this example, let's change the password for the user "alice":

$ sudo passwd alice

\[sudo\] password for your\_username: \[enter your sudo password\]

Changing password for user alice.

New password: \[enter the new password for alice\]

Retype new password: \[retype the new password for alice\]

passwd: password updated successfully

_**Command: date**_

The date command in Linux is used to display or set the current system date and time. When executed without any options, it simply prints the current date and time in the default format, which typically includes the day of the week, month, day, time, timezone, and year.

However, you can customize the output format using various options available with the date command. It is also possible to use the date command to set the system's date and time if you have the appropriate permissions.

Displaying the date and time in a specific format:

%a: Abbreviated weekday name (e.g., Sun).

%A: Full weekday name (e.g., Sunday).

%b: Abbreviated month name (e.g., Jan).

%B: Full month name (e.g., January).

%d: Day of the month (01 to 31).

%H: Hour in 24-hour format (00 to 23).

%I: Hour in 12-hour format (01 to 12).

%M: Minute (00 to 59).

%S: Second (00 to 60).

%Y: Year with century (e.g., 2023).

%y: Year without century (e.g., 23).

%Z: Timezone name (e.g., UTC).

**Example: Display date in given format**

$ date +"%A, %d %B %Y"

Sunday, 31 July 2023

**Example: Setting the system date and time**

To set the date and time, you need superuser (root) privileges. The format to set the date is usually "MMDDhhmm\[\[CC\]YY\]\[.ss\]" where MM is the month, DD is the day, hh is the hour, mm is the minute, CC is the first two digits of the year (century), YY is the last two digits of the year, and ss is the seconds.

$ sudo date MMDDhhmm\[\[CC\]YY\]\[.ss\]

$ sudo date 073110302023.30

Sets the date to July 31, 2023, 10:30 AM and 30 seconds.

**Example: Displaying a date relative to the current date**

+n days: Display the date n days in the future.

−n days: Display the date n days in the past.

**Add 2 days to the current date**

$ date "+%A, %d %B %Y" -d "+2 days"

Tuesday, 02 August 2023

**Check the new date**

$ date

Sun Jul 31 10:30:00 UTC 2023

_**Command: who**_

The who command provides information about currently logged-in users on the system. It displays details such as the username, terminal, date, and time of the login. If used without any options, it shows a list of all logged-in users on the system. This can be useful for system administrators to monitor active sessions and check who is currently using the system.

**Example:**

$ who

john pts/0 2023-07-31 09:45 (:0)

alice pts/1 2023-07-31 10:00 (:0)

_**Command: whoami**_

The whoami command is used to print the username of the current user who is executing the command. It is helpful when you need to know the current user's identity, especially in shell scripts or when managing file permissions and access control.

Example:

$ whoami

John

**Options**

**\-q or --count** Gives number of users currently logged in

**\-H or --head** Displays the header line

**who -q or who --count:**

$ who -q

\# users=2

**who -H or who --heading:**

The -H option displays a header line, indicating the meaning of each column in the output.

$ who -H

NAME LINE TIME COMMENT

john tty1 2023-07-31 09:45 (:0)

alice pts/0 2023-07-31 10:00 (:0)

_**Command: write \[username\]**_

The write command in Linux allows users to send messages to other logged-in users on the same system. It is a simple and efficient way to communicate with other users who are currently using the terminal.

The basic syntax of the write command is as follows:

write \[username\] \[terminal\]

Here, username is the username of the user to whom you want to send the message, and terminal is the terminal or device number where the recipient is logged in. If terminal is not specified, the message is sent to the user's terminal where the write command was executed.

**Example:**

$ write john

After entering this command, you can type your message, and the recipient (in this case, the user "john") will receive your message on their terminal.

**Options for the write command:**

write -h or write --help:

Displays the help message, which includes a brief description of the write command and its usage.

write -V or write --version:

Shows the version information of the write command.

write -t timeout or write --timeout=timeout:

Specifies the duration (in seconds) after which the write command times out if the recipient does not respond. If the timeout is reached, the message will not be sent.

_**Command: man**_

The man command in Linux is used to display the manual pages (documentation) for other commands or programs installed on your system. It provides comprehensive information about the usage, options, and functionality of various commands.

_**man \[command\]:**_ This is the basic syntax for using the man command. Replace \[command\] with the name of the command you want to know more about. For example, man ls will display the manual page for the ls command.

_**man -k \[keyword\] or man -f \[keyword\]:**_ These options allow you to search for commands by a specific keyword. For instance, man -k network will list all commands related to "network."

_**man -a \[command\]:**_ When multiple manual pages exist for the same command (e.g., from different software packages), using this option will display all the available manual pages for the specified command.

_**man -w \[command\]:**_ This option prints the path to the manual page file for the given command, allowing you to locate where the documentation is stored on your system.

_**man --help or man -h:**_ These options display a short summary of the man command itself, including the available options and how to use them.

_**man --sections \[section\_number\] \[command\]:**_ Manual pages are categorized into different sections (e.g., 1 for commands, 2 for system calls, 3 for library functions). Using this option, you can specify a section number to view the manual page from a particular section. For example, man --sections 3 printf will show the manual page for the printf library function.

_**Example:**_

man ls

After pressing Enter, the man command will display the manual page for the ls command. You can scroll through the page using the arrow keys, and to exit the manual page, press q.

The manual page for ls will provide you with detailed information about how to use the command, including a description of its functionality, available options, and usage examples.

## **3\. Linux Basic Commands: ln, pwd, and ls with options**

_**Command: ln \[options\] source\_file target\_file**_

The ln command in Linux is used to create links between files or directories. Links are essentially pointers to the original file or directory, and they allow multiple filenames to refer to the same data on disk. The ln command has two primary types of links: hard links and symbolic links (also known as soft links). Here are some short notes on the ln command with its options:

**Basic Syntax:**

ln \[OPTION\]... \[-T\] TARGET LINK\_NAME

**Creating Hard Links:**

Hard links are direct references to the same inode (data) on disk as the original file. If you modify the hard link's content, it affects the original file and vice versa. Hard links can't link to directories and cannot span across different filesystems (partitions).

By default, ln creates hard links.

**Creating Symbolic Links (Soft Links):**

Symbolic links are references to the path of the original file or directory. They act as shortcuts, and if you modify the symbolic link, it doesn't affect the original file. Symbolic links can link to directories and can span across different filesystems.

To create a symbolic link, use the -s option.

**Usage Examples: Creating a hard link:**

ln file.txt hardlink.txt

**Usage Examples: Creating a symbolic link:**

ln -s file.txt symlink.txt

**Usage Examples: Overwriting existing link without prompting:**

ln -sf newfile.txt existinglink

**Usage Examples: Creating a symbolic link to a directory:**

ln -s /path/to/source\_directory link\_to\_directory

Remember that when you delete a link (hard link or symbolic link), it does not affect the original file or directory.

_**Command: pwd**_

The pwd command in Linux stands for "print working directory." It is used to display the current working directory, which is the directory in the file system where the user is currently located. The pwd command is a simple and useful tool for quickly identifying the directory path, which can be handy while navigating through the file system or working with relative paths.

**Basic Syntax:**

pwd \[OPTION\]

**Common Options:**

**pwd (no options):**

When pwd is used without any options, it prints the absolute path of the current working directory, starting from the root of the filesystem.

**Example:**

$ pwd

/home/user/documents

**pwd -L or pwd --logical:**

This option prints the logical path of the current directory. It does not resolve symbolic links in the path. If the current directory is a symbolic link to another directory, pwd -L will show the path of the symbolic link itself.

**Example:**

$ pwd -L

/home/user/documents

**pwd -P or pwd --physical:**

This option prints the physical path of the current directory, resolving symbolic links along the path. If the current directory is a symbolic link, pwd -P will show the actual path of the target directory.

**Example:**

$ pwd -P

/mnt/storage/docs

Using the appropriate option depends on whether you want to see the physical path (resolved symbolic links) or the logical path (without resolving symbolic links) of the current directory. By default, the pwd command behaves as pwd -P, showing the physical path.

_**Command: ls \[options\] \[directory\]**_

The ls command in Linux is used to list the files and directories in a specified directory. It is one of the most commonly used commands in the Linux command-line interface for exploring the filesystem. The ls command provides various options to customize the output and display additional information about files and directories.

**Basic Syntax:**

ls \[OPTION\]... \[FILE\]...

**Common Options:**

**ls (no options):**

When ls is used without any options, it lists the files and directories in the current working directory (usually the directory where the user is currently located).

**Example:**

$ ls

file1.txt file2.txt directory1 directory2

**ls -l or ls --long:**

This option displays the files and directories in a detailed, long listing format. It shows additional information such as file permissions, owner, group, file size, modification date, and the name of each entry.

**Example:**

$ ls -l

\-rw-r--r-- 1 user group 1024 Jul 31 10:00 file1.txt

\-rw-r--r-- 1 user group 2048 Jul 31 10:15 file2.txt

drwxr-xr-x 2 user group 4096 Jul 31 10:30 directory1

drwxr-xr-x 2 user group 4096 Jul 31 10:45 directory2

**ls -a or ls --all:**

This option includes hidden files and directories in the listing. Hidden entries in Linux start with a dot (e.g., .hidden\_file).

**Example:**

$ ls -a

. .. file1.txt file2.txt .hidden\_file directory1 directory2

**ls -h or ls --human-readable:**

This option makes file sizes human-readable by displaying them in a more understandable format, using units such as KB, MB, GB, etc.

**Example:**

$ ls -lh

\-rw-r--r-- 1 user group 1.0K Jul 31 10:00 file1.txt

\-rw-r--r-- 1 user group 2.0K Jul 31 10:15 file2.txt

drwxr-xr-x 2 user group 4.0K Jul 31 10:30 directory1

drwxr-xr-x 2 user group 4.0K Jul 31 10:45 directory2

These are just a few of the options available for the ls command. To see the complete list of options and their descriptions, you can check the manual page for the ls command by running man ls in the terminal.

## **4\. Linux Basic Commands: touch, tr, and pr**

_**Command: touch \[filename\]**_

The touch command in Linux is used to create an empty file or update the access and modification times of an existing file. It is a versatile command that allows users to create new files quickly or modify the timestamps of existing ones.

**Basic Syntax:**

touch \[OPTION\]... FILE...

**Common Options:**

**touch FILENAME:**

When touch is used without any options, it creates an empty file with the specified filename. If the file already exists, it updates the access and modification times to the current time without modifying the file's content.

**Example:**

$ touch myfile.txt

**touch -a or touch --time=access:**

This option changes only the access time of the file, leaving the modification time unchanged.

**Example:**

$ touch -a myfile.txt

**touch -m or touch --time=modification:**

This option changes only the modification time of the file, leaving the access time unchanged.

**Example:**

$ touch -m myfile.txt

The touch command is a powerful tool for managing file timestamps and creating new files in a straightforward manner.

_**Command: tr \[options\] \[set1\] \[set2\]**_

The tr command in Linux is a versatile utility used for translating, deleting, or squeezing characters in a given input stream. It is primarily used for text manipulation and can be quite handy for simple string transformations. The name "tr" stands for "translate."

**Basic Syntax:**

tr \[OPTION\]... SET1 \[SET2\]

**Common Options:**

**tr \[SET1\] \[SET2\]:**

The most basic form of the tr command requires two sets of characters, SET1 and SET2. It reads the input from the standard input (stdin) and replaces characters from SET1 with the corresponding characters from SET2.

**Example:**

$ echo "hello" | tr 'aeiou' 'AEIOU'

hEllO

**tr -d \[SET\] or tr --delete \[SET\]:**

The -d option deletes all characters from the input that are listed in the SET.

**Example:**

$ echo "hello" | tr -d 'l'

heo

**tr -s or tr --squeeze-repeats:**

The -s option squeezes repeated occurrences of characters in the input to a single character. It removes consecutive duplicates.

**Example:**

$ echo "aaabbbccc" | tr -s 'a'

abbbccc

**tr -c \[SET\] or tr --complement \[SET\]:**

The -c option complements the SET specified. It replaces all characters not listed in the SET.

**Example:**

$ echo "hello" | tr -c 'a-z' 'X'

XXXXX

The tr command is frequently used for basic character conversions, removing unwanted characters, and replacing characters in text streams. It is particularly useful in shell scripts and one-liners for text manipulation tasks. For more advanced text processing or complex pattern matching, other tools like sed or awk may be more appropriate.

_**Command: pr \[options\] \[filename\]**_

The pr command in Linux is used for formatting and paginating text files before printing. It enables users to adjust the layout of text and control the appearance of text on printed pages. While its primary purpose is to format files for printing, the pr command can also be useful for viewing text in a more organized manner on the terminal.

**Basic Syntax:**

pr \[OPTION\]... \[FILE\]...

**Common Options:**

**pr \[FILE\]:**

When pr is used without any options, it paginates the text file and prints it on the standard output (usually the terminal) with default formatting.

**Example:**

$ pr myfile.txt

**pr -n \[NUMBER\] or pr --columns=\[NUMBER\]:**

The -n option specifies the number of columns in the output. By default, pr uses two columns. The output will be formatted to fit the specified number of columns, wrapping text appropriately.

**Example:**

$ pr -n 4 myfile.txt

**pr -l \[NUMBER\] or pr --length=\[NUMBER\]:**

The -l option sets the page length to the specified number of lines. pr breaks the output into pages based on the line length.

**Example:**

$ pr -l 30 myfile.txt

**pr -h \[HEADER\] or pr --**header=\[HEADER\]:

The -h option allows you to add a header to each page of the output.

**Example:**

$ pr -h "Report" myfile.txt

**pr -o \[NUMBER\] or pr --omit-pagination=\[NUMBER\]:**

The -o option specifies the number of initial lines to omit from pagination. The omitted lines are not included in the page count.

**Example:**

$ pr -o 5 myfile.txt

The pr command is useful when you want to format text files for printing or create structured and readable output on the terminal. It is often used in combination with other commands in shell scripts to produce well-organized reports or display text content with custom formatting.

Remember to explore the manual pages for these commands to discover more options and their usage.

## **Reading Summary**

In this reading, you have learned the following:

-   Life cycle of a user session in Linux
    
-   Some important Linux commands and their usage


## **Reading Objective**

In this reading, you will gain insights into some of the network-related commands in Linux like hostname, ping, traceroute, and nmap. This reading also covers some Linux basic commands such as ssh, scp, and /etc/ssh.

## **Linux Commands: hostname, ping, traceroute, and nmap**

## **hostname command:**

The hostname command in Linux is used to display or set the system's hostname. The hostname is a label assigned to the computer on a network, and it helps identify the machine within the network.

_**hostname:**_ When used without any options, the hostname command displays the current hostname of the system.

_**hostname -f:**_ The -f option stands for "fully qualified domain name." It displays the complete domain name associated with the hostname.

_**hostname -i:**_ The -i option displays the IP addresses associated with the system's hostname.

_**hostname -s:**_ The -s option stands for "short" or "simple." It displays only the short name (the hostname without the domain name).

**Examples:**

Display the current hostname:

hostname

Display the fully qualified domain name:

hostname -f

Display the IP addresses associated with the hostname:

hostname -i

Display only the short name (hostname without the domain name):

hostname -s

## **ping command:**

The ping command in Linux is used to test network connectivity between a source and a destination. It sends Internet Control Message Protocol (ICMP) Echo Request packets to the destination and waits for ICMP Echo Reply packets to measure the round-trip time and packet loss.

_**ping host:**_ The basic syntax of the ping command requires you to specify the hostname or IP address of the destination you want to test connectivity with.

_**ping -c count host:**_ The -c option specifies the number of packets to send (count). It stops pinging after sending the specified number of packets.

_**ping -i interval host:**_ The -i option sets the interval (in seconds) between successive packet transmissions.

_**ping -W timeout host:**_ The -W option sets the timeout (in seconds) for waiting for a response before considering the packet lost.

_**ping -R host:**_ The -R option records the route taken by packets in the output.

_**ping -6 host:**_ The -6 option forces the use of IPv6 when pinging a host.

**Examples:**

Basic ping test to a host:

ping google.com

Ping a host four times:

ping -c 4 example.com

Set the interval between pings to 2 seconds:

ping -i 2 example.com

The ping command is a simple yet powerful tool for testing network connectivity. It is commonly used for diagnosing network-related issues, verifying if a host is reachable, and assessing network performance.

## **traceroute command:**

The traceroute command in Linux is used to trace the route that packets take from the source to a destination over a network. It provides valuable information about the network path, including the IP addresses of intermediate routers and the round-trip time (latency) for each hop.

_**traceroute host:**_ The basic syntax of the traceroute command requires you to specify the hostname or IP address of the destination you want to trace the route to.

_**traceroute -I host:**_ The -I option forces the use of ICMP Echo Request packets instead of UDP. Some routers may block UDP traceroute, making ICMP traceroute a more reliable option.

_**traceroute -n host:**_ The -n option disables hostname resolution, showing IP addresses instead of hostnames in the output.

_**traceroute -w timeout host:**_ The -w option sets the timeout (in seconds) for each probe.

**Examples:**

Basic traceroute to a host:

traceroute example.com

Traceroute using ICMP Echo Request (ICMP-based traceroute):

traceroute -I example.com

The traceroute command is a valuable network diagnostic tool that helps identify network delays, packet loss, and routing issues. It provides insights into the path taken by packets across networks, making it useful for network troubleshooting and analysis.

## **nmap command:**

The nmap command in Linux is a powerful network scanning tool used to discover hosts and services on a computer network. It provides a wide range of options to scan hosts for open ports, detect operating systems, and gather information about network services.

_**nmap target:**_ The basic syntax of the nmap command requires you to specify the target IP address or hostname you want to scan.

_**nmap -p ports target:**_ The -p option specifies the ports to scan. You can specify individual ports or port ranges separated by commas.

_**nmap -F target:**_ The -F option (Fast Scan) scans only the most common 100 ports, providing a quicker scan result.

_**nmap -A target:**_ The -A option enables aggressive scanning, which includes OS detection, version detection, script scanning, and traceroute.

_**nmap -O target:**_ The -O option attempts to detect the remote operating system.

**Examples:**

Basic scan of a single target:

nmap 192.168.1.1

Scan specific ports on a target:

nmap -p 80,443 example.com

Aggressive scan with OS detection and version detection:

nmap -A 192.168.0.1

The nmap command is an essential tool for network administrators and security professionals to discover and assess the security of their networks. It helps identify open ports, services, and potential vulnerabilities that can aid in securing the network infrastructure.

## **Linux Basic Commands: ssh, scp and /etc/ssh**

## **SSH (Secure Shell)**

SSH (Secure Shell) is a cryptographic network protocol used to securely access and manage remote systems over an unsecured network. It provides encrypted communication between the client and the server, ensuring data confidentiality and integrity.

**Syntax:**

ssh \[options\] \[user@\]hostname \[command\]

**Common Options:**

\-p port: Specify a custom SSH port (default is 22).

\-i identity\_file: Use a specific private key for authentication.

**Example:**

ssh user@example.com

Connects to the example.com server using SSH.

## **SCP (Secure Copy)**

SCP (Secure Copy) is a command-line utility for securely copying files between local and remote systems using SSH for data transfer.

**Syntax:**

scp \[options\] \[source\] \[destination\]

**Common Options:**

\-P port: Specify a custom SSH port (default is 22).

\-i identity\_file: Use a specific private key for authentication.

\-r: Recursively copy directories and their contents.

**Example:**

scp file.txt user@example.com:/path/to/destination

Copies file.txt from the local system to the remote host example.com at /path/to/destination.

## **/etc/ssh (SSH Configuration Directory)**

The /etc/ssh directory contains configuration files for the OpenSSH server and client. It allows administrators to customize SSH behavior and enhance security.

**Important Files:**

sshd\_config: Configuration file for the SSH server (sshd).

ssh\_config: Configuration file for the SSH client (ssh).

ssh\_host\_\*: Files containing host keys used for server authentication.

ssh\_known\_hosts: System-wide file containing known host keys.

**Note:**

Modifying SSH configuration files requires administrative privileges. Always create backups before making changes.

## **Reading Summary**

In this reading, you have learned the following:

-   Network-related commands in Linux like hostname, ping, traceroute, and nmap
    
-   Some Linux basic commands such as ssh, scp, and /etc/ssh





## **Reading Objective:**

In this reading, you will learn about the basics of files and Linux file systems. You will also learn about the file permissions in Linux. This reading will help you gain an understanding of inode and inode structure in Linux. This reading also focuses on links in Linux, and inode associated with directories and access permissions.

## **1\. Basics of Files and Linux File System**

## **Introduction to Files:**

A file is a collection of data or information stored on a computer. It can contain various types of data, such as text, images, videos, or program instructions. Files are essential for storing and organizing data on a computer system, enabling data persistence and easy access.

## **Linux File System:**

The Linux File System is a hierarchical structure that organizes and manages files and directories (folders) in Linux-based operating systems. The file system provides a unified way of accessing and managing data stored on different storage devices, such as hard drives, SSDs, and external drives.

## **File Paths:**

In Linux, a file path is a textual representation of a file's location within the file system hierarchy. It starts from the root directory ("/") and navigates through directories until reaching the desired file. Paths can be absolute (starting from the root) or relative (starting from the current working directory).

## **Directories (Folders):**

Directories, also known as folders, are special types of files that can contain other files and directories. They are used to organize files hierarchically, making it easier to manage and locate data.

## **Working Directory:**

The working directory is the directory in which the user is currently operating or executing commands. When you open a terminal, you are typically in your home directory, and you can navigate to different directories using commands like cd (change directory).

## **File Permissions:**

Linux uses a permission system to regulate access to files and directories. There are three types of permissions: read, write, and execute. Permissions can be set for three groups: owner, group, and others. The **chmod** command is used to change file permissions.

## **Basic File Operations:**

**Common file operations in Linux include:**

Creating a new file: **touch** filename

**Example:**

**touch** example.txt

Copying files: **cp** sourcefile destination

**Example:**

cp source.txt destination.txt

Moving files (also used for renaming):

Moving files: **mv** sourcefile destination (also used for renaming)

**Example:**

mv oldname.txt newname.txt

mv file.txt /path/to/new/location/

Removing files: **rm** filename

**Example:**

rm unwanted\_file.txt

Listing files: **ls**

**Example:**

ls

Listing files with detailed information, including permissions and ownership:

ls -l

Listing all files, including hidden files:

ls -a

## **File Ownership:**

Every file in Linux is associated with an owner and a group. The chown command is used to change the file's owner, while the chgrp command is used to change its group ownership.

**Example:**

chmod 644 example.txt # Sets read and write permissions for the owner and read-only for the group and others

Changing file ownership:

**Example:**

chown user:group example.txt

Changing group ownership:

**Example:**

chgrp newgroup example.txt

## **File System Navigation:**

To navigate the Linux file system, you can use commands like:

**cd**: Change directory

**Example:**

cd /path/to/directory/

**pwd**: Print working directory

**Example:**

pwd

**cd ..**: Move up one level in the directory hierarchy

## **File Extensions:**

Unlike some other operating systems, _**Linux does not rely heavily on file extensions to determine file types**_. Instead, it uses file permissions and file content to identify the file type. However, file extensions are still commonly used to give users a hint about the file's content or intended use.

Understanding the basics of files and the Linux file system is crucial for effectively managing data, performing operations, and maintaining the security and integrity of your system. Learning more advanced file system concepts can greatly enhance your proficiency in Linux administration and usage.

## **2\. File Permissions**

-   File permissions in Linux determine who can perform various operations (read, write, execute) on a file.
    
-   Each file has three sets of permissions: one for the owner, one for the group, and one for others (everyone else).
    
-   These permissions can be represented using a combination of letters and numbers.
    

## **File Permission Representation:**

Read: r (denoted by the number 4)

Write: w (denoted by the number 2)

Execute: x (denoted by the number 1)

**Numerical Representation:**

Each set of permissions (owner, group, others) can be represented by a three-digit number, where each digit represents the sum of the corresponding permissions. For example:

0: No permissions (---)

1: Execute-only (--x)

2: Write-only (-w-)

3: Write and execute (-wx)

4: Read-only (r--)

5: Read and execute (r-x)

6: Read and write (rw-)

7: Read, write, and execute (rwx)

## **Viewing File Permissions:**

To view the permissions of files in the current directory, you can use the ls -l command. It will display a list of files along with their permissions, ownership, and other details. For example:

**ls -l**

\-rw-r--r-- 1 user group 1024 Aug 3 10:00 example.txt

## **Changing File Permissions:**

The chmod command is used to change file permissions. There are two ways to use chmod:

**Symbolic notation:** This method uses symbols (+, −, =) to add, remove, or set permissions. For example:

chmod +x script.sh # Adds execute permission for all (owner, group, others)

chmod u+w file.txt # Adds write permission for the owner

chmod go-r file.txt # Removes read permission for the group and others

chmod o=rw file.txt # Sets read and write permissions for others

**Octal notation:** This method uses the numerical representation (0–7) to specify permissions directly. For example:

chmod 644 example.txt # Sets read and write permissions for the owner and read-only for the group and others

chmod 755 script.sh # Sets read, write, and execute for the owner, and read and execute for the group and others

## **Default Permissions:**

When you create a new file or directory, it inherits permissions from the parent directory. The default permissions can be modified using the umask command, which subtracts the specified value from the maximum permissions (777 for directories, 666 for files) to get the default permissions.

Understanding and managing file permissions is crucial for maintaining security and controlling access to files on a Linux system. Be cautious while changing permissions, as incorrect settings can lead to unintended consequences or security vulnerabilities.

## **3\. Inode and inode structure in Linux**

## **Introduction to inode:**

Inodes are a fundamental concept in Unix-like file systems, including Linux. An inode (index node) is a data structure that stores metadata about a file, except its name and actual data content. Each file in the file system is associated with a unique inode, which contains crucial information about the file, such as its permissions, ownership, timestamps, size, and disk block locations.

## **Inode Structure:**

The inode structure in Linux typically contains the following important fields:

_**File Type:**_ Indicates whether the inode corresponds to a regular file, directory, symbolic link, device file, etc.

_**File Permissions:**_ Specifies the access permissions for the file, such as read, write, and execute permissions for the owner, group, and others.

_**Ownership:**_ Stores the user ID (UID) and group ID (GID) of the file owner and associated group.

_**Timestamps:**_ Records the last access time, last modification time, and last status change time of the file.

_**File Size:**_ Indicates the size of the file in bytes.

_**Number of Links:**_ Represents the number of hard links pointing to the same inode (used for file reference counting).

_**Disk Block Pointers:**_ Stores pointers to the data blocks on the disk that hold the file's content. For small files, the inode contains direct block pointers, while for larger files, it includes indirect and double indirect pointers to locate data blocks.

## **Associated Commands:**

Several Linux commands allow you to interact with inodes and retrieve inode-related information:

**ls -i:** Lists files along with their associated inode numbers.

**stat:** Displays detailed information about a file, including inode number, permissions, timestamps, and more.

**stat** filename

**find:** Can be used to search for files based on various criteria, including inode number.

**find** /path/to/search -inum <inode\_number>

**df -i:** Shows inode-related information for the file systems mounted on the system.

**debugfs:** A powerful command-line tool to interactively view and manipulate the file system's internal structures, including inodes. Use it with caution as it provides low-level access to the file system.

**debugfs** /dev/sdaX# Replace 'X' with the appropriate partition number.

## **Importance of inodes:**

Inodes play a crucial role in the management of file systems. Some key benefits of using inodes include:

_**Efficient storage management:**_ Inodes allow the file system to manage files of various sizes effectively and allocate disk blocks efficiently.

_**Multiple links:**_ Inodes support the concept of hard links, enabling multiple directory entries to point to the same file content.

_**Fast file access:**_ The use of inodes allows the file system to locate and retrieve file metadata and content quickly.

In summary, inodes are essential data structures in Linux file systems that hold crucial information about files. Understanding how inodes work can provide insights into file system performance and behavior, making it easier to manage and troubleshoot storage-related issues.

## **4\. Links in Linux**

## **Introduction to Links:**

In Linux, links are used to create references to files and directories. Links allow multiple paths to access the same underlying data, enabling efficient data organization and management. There are two types of links in Linux: Hard Links and Symbolic Links.

## **1\. Hard Links:**

-   A hard link is a direct link to the inode of a file. It shares the same inode number as the original file and points directly to the data blocks containing the file's content.
    
-   Changes made to one hard link are reflected in all hard links that share the same inode. All hard links are essentially equivalent; there is no concept of a "source" or "target" hard link.
    
-   Hard links cannot span across different file systems or partitions because they are based on the inode, which is specific to each file system.
    
-   If the original file is deleted, the data remains accessible through the hard links as long as there is at least one hard link pointing to the inode.
    

## **Associated Commands for Hard Links:**

**Creating a hard link:**

ln /path/to/originalfile /path/to/hardlink

**Checking the number of hard links to a file:**

ls -l /path/to/file

**Deleting a hard link (does not affect the original file):**

rm /path/to/hardlink

## **2\. Symbolic Links (Soft Links):**

-   A symbolic link, or soft link, is a special file that contains the path to another file or directory. It references the target file by its path name, rather than using the inode directly.
    
-   Symbolic links can span across different file systems or partitions because they use the file path instead of the inode.
    
-   Deleting the original file will render the symbolic link broken, as it will point to a nonexistent target.
    

## **Associated Commands for Symbolic Links:**

**Creating a symbolic link:**

ln -s /path/to/originalfile /path/to/symlink

**Checking if a file is a symbolic link:**

ls -l /path/to/file

**Deleting a symbolic link (does not affect the target file):**

rm /path/to/symlink

## **Tips and Best Practices:**

-   Hard links cannot reference directories; use symbolic links for linking directories.
    
-   Avoid creating symbolic links with relative paths if the target may be moved, as it can break the link.
    
-   When removing files with hard links, ensure to delete the last hard link to free the disk space fully.
    

Links in Linux provide powerful tools for managing file and directory references efficiently. Hard links allow multiple names to refer to the same file's data blocks, while symbolic links create references based on file paths. Understanding and correctly using links contribute to a well-organized and easily maintainable file system.

## **5\. Inode Associated with Directories and Access Permissions**

## **Inode and Directories:**

In Linux, directories are also represented by inodes. An inode associated with a directory contains metadata about the directory, such as its permissions, ownership, timestamps, and a list of filenames along with their corresponding inode numbers. The directory's inode points to the data blocks that store the filenames and their respective inodes. This hierarchical structure allows the file system to organize and access files efficiently.

## **Access Permissions on Directories:**

Access permissions on directories are distinct from those on regular files. Directory permissions control what actions users can perform within the directory, such as listing its contents, creating, renaming, or deleting files within it.

## **The three main permissions for directories are:**

1.  **Read (r):** If a user has read permission on a directory, they can view the list of files and subdirectories within the directory using commands like ls.
    
2.  **Write (w):** Write permission on a directory allows users to create, delete, and rename files or directories within it. They can also modify the contents of files within the directory if they have the appropriate permissions on those files.
    
3.  **Execute (x):** Execute permission on a directory is required to access its contents. Without execute permission, users won't be able to change their working directory to the directory or access files within it.
    

## **Effects of Access Permissions on Directories:**

**Read Permission:** Users with read permission can see the filenames and subdirectory names within the directory. However, they cannot access files or subdirectories unless they have the appropriate permissions on those objects.

**Write Permission:** Users with write permission can add or delete files or directories within the directory. They can also rename files or directories within the directory if they have write permission on the parent directory.

**Execute Permission:** Execute permission is essential for accessing the contents of a directory. Without execute permission, users won't be able to use the directory's name to access its contents or change their working directory to it.

## **Setting Directory Permissions:**

You can use the chmod command to set permissions on directories.

**For example:**

chmod 755 directory\_name

The above command grants read, write, and execute permissions to the owner and read and execute permissions to the group and others.

## **Directory Access Permissions and Security:**

Properly managing directory access permissions is crucial for maintaining the security and privacy of your files. Setting appropriate permissions ensures that only authorized users can access, modify, or delete files within the directory. Avoid granting unnecessary permissions to prevent unauthorized access.

Understanding the relationship between inodes and directories, as well as the significance of directory access permissions, helps in effectively organizing and securing data within a Linux file system.

## **Reading Summary**

In this reading, you have learned the following:

-   Basics of files and Linux file system
    
-   File permissions
    
-   Inode and inode structure in Linux
    
-   Links in Linux
    
-   Inode associated with directories and access permissions




## **Reading Objective:**

In this reading, you will learn about the Linux commands for navigating and listing files in the directory. This reading will give a brief overview of commands like cd, pwd, Is, Is-I, Is-a, Is-h, Is-t, Is-R. You will also learn about the Linux commands, used for creating and deleting files and directories, and for copying and moving files and directories. The reading will also focus on the Linux commands for permissions and ownership of a file or directory, disk usage, and link.

## **1\. File and Directory Commands**

## **Linux Commands for Navigating and Listing Files in the Directory**

## **cd - Change Directory:**

The cd command is used to change the current working directory in the Linux terminal. It allows you to navigate to a different directory. If you omit any path, cd will take you to your home directory.

**Example:**

cd /path/to/directory

cd .. # Move up one level in the directory hierarchy

cd ~ # Go to the home directory

## **pwd - Print Working Directory:**

The pwd command prints the full path of the current working directory.

**Example:**

pwd

## **ls - List Files and Directories:**

The ls command is used to list files and directories in the current working directory. By default, it shows only the names of visible files and directories.

**Examples:**

ls

ls /path/to/directory

## **ls -l - Long Format Listing:**

The ls -l command provides a detailed listing of files and directories in the long format. It includes additional information like permissions, owner, group, size, modification date, and filename.

**Example:**

ls -l

## **ls -a - List Hidden Files:**

The ls -a command shows all files, including hidden files (files whose names start with a dot .). Hidden files are usually configuration files or directories that are not displayed by default.

**Example:**

ls -a

## **ls -h - Human-Readable File Sizes:**

The ls -h command displays file sizes in a human-readable format, using units like KB, MB, GB, etc., instead of just displaying bytes.

**Example:**

ls -lh

## **ls -t - Sort by Modification Time:**

The ls -t command sorts files and directories based on their modification time, with the newest files shown first.

**Example:**

ls -lt

## **ls -R - Recursive Listing:**

The ls -R command lists files and directories recursively, showing the content of subdirectories as well.

**Example:**

ls -R

These Linux commands for navigating and listing files in the directory provide essential tools for exploring the file system, managing files, and finding the information you need efficiently. Combining these commands with different options allows you to tailor the output according to your requirements.

## **2\. Linux Commands for Creating and Deleting Files and Directories**

## **touch - Create Empty Files or Update Timestamps:**

The touch command is used to create an empty file or update the timestamps (access and modification) of an existing file. If the file already exists, touch will update its timestamps to the current time.

**Examples:**

touch filename # Create an empty file named 'filename'

touch file1 file2 # Create multiple empty files

touch -a file.txt # Update only the access time

touch -m file.txt # Update only the modification time

## **mkdir - Create Directories:**

The mkdir command is used to create directories (folders) in the file system.

**Examples:**

mkdir dirname # Create a directory named 'dirname'

mkdir -p /path/to/directory# Create parent directories if they don't exist

## **rm - Remove (Delete) Files or Directories:**

The rm command is used to remove (delete) files or directories. By default, it does not delete directories, but you can use the -r option (recursive) to remove directories and their contents.

**Examples:**

rm filename # Remove a file named 'filename'

rm file1 file2 # Remove multiple files

rm -r dirname # Remove a directory and its contents recursively

rm -rf /path/to/directory # Forcefully remove a directory and its contents

## **rmdir - Remove Empty Directories:**

The rmdir command is used to remove empty directories from the file system. It cannot remove directories with contents.

**Example:**

rmdir empty\_directory# Remove an empty directory named 'empty\_directory'

## **3\. Linux Commands for Copying and Moving Files and Directories**

## **cp - Copy Files and Directories:**

The cp command is used to copy files or directories from one location to another. It can copy single or multiple files and directories. If copying directories, the -r (recursive) option is required to copy the directory and its contents.

**Examples:**

cp file.txt /path/to/destination # Copy a file to a new location

cp file1.txt file2.txt /path/to/destination # Copy multiple files to a directory

cp -r directory /path/to/destination # Copy a directory and its contents to a new location

## **mv - Move (Rename) Files and Directories:**

The mv command is used to move (rename) files or directories. If the source and destination are on the same filesystem, mv will perform a move operation. Otherwise, it will perform a rename. This command is also used to rename files or directories.

**Examples:**

mv oldname.txt newname.txt # Rename a file

mv file.txt /path/to/directory # Move a file to a different location

mv file1.txt file2.txt /path/to/directory # Move multiple files to a directory

These Linux commands provide various options for copying and moving files and directories, making it easy to organize and transfer data efficiently within a file system or between systems.

## **4\. Linux Commands for Permissions and Ownership of a File or Directory**

## **chmod - Change File Permissions:**

The chmod command is used to change the permissions of a file or directory. It allows you to modify read (r), write (w), and execute (x) permissions for the owner, group, and others.

_**Symbolic notation:**_ You can use symbols (+, −, =) to add, remove, or set permissions.

**For example:**

chmod +x script.sh # Adds execute permission for all (owner, group, others)

chmod u+w file.txt # Adds write permission for the owner

chmod go-r file.txt # Removes read permission for the group and others

chmod o=rw file.txt # Sets read and write permissions for others

_**Octal notation:**_ You can use numerical representation (0–7) to specify permissions directly.

**For example:**

chmod 644 example.txt # Sets read and write permissions for the owner and read-only for the group and others

chmod 755 script.sh # Sets read, write, and execute for the owner, and read and execute for the group and others

## **chown - Change File Ownership:**

The chown command is used to change the owner and/or group ownership of a file or directory. You can specify the new owner and group using the user and group names or their corresponding user IDs (UID) and group IDs (GID).

**Examples:**

chown user:group file.txt # Change the owner and group of the file

chown user file.txt # Change only the owner of the file

chown :group file.txt # Change only the group of the file

chown user: file.txt # Remove the group ownership (set group to default)

## **chgrp - Change Group Ownership:**

The chgrp command is used to change the group ownership of a file or directory. You can specify the new group using the group name or its corresponding GID.

**Example:**

chgrp group file.txt # Change the group of the file

## **ls with -l Option - Display Permissions and Ownership:**

The ls command with the -l option provides a detailed listing that includes permissions, ownership, timestamps, and more for files and directories.

**Example:**

ls -l

## **id - Display User and Group Information:**

The id command displays the current user's UID, GID, and group membership. It is useful to identify the current user's ownership when dealing with file permissions.

**Example:**

id

**Note:** Changing permissions and ownership should be done with caution, as it can affect file access and security. Always ensure that you have the necessary permissions to perform such operations and carefully verify your changes before applying them, especially when altering system files or directories.

These Linux commands provide powerful tools for managing file permissions and ownership, allowing you to control access and maintain security within your file system.

## **5\. Linux Commands for Disk Usage and Links**

## **du - Disk Usage:**

The du command is used to estimate and display the disk usage of files and directories in the file system. It helps you identify which directories or files consume the most disk space.

**Options:**

\-h: Displays sizes in human-readable format (e.g., KB, MB, GB).

\-s: Displays only the total size of each argument (directory).

\-c: Includes a grand total of disk usage at the end of the output.

**Examples:**

du -h # Displays disk usage of current directory and its subdirectories

du -h /path/to/directory # Displays disk usage of a specific directory

du -sh /path/to/directory # Displays only the total disk usage of the directory

du -h --max-depth=1 # Displays disk usage of immediate subdirectories only

du -ch /path/to/directory # Displays the total disk usage, including the grand total

## **df - Disk Free:**

The df command shows the amount of free and used disk space on mounted file systems. It provides an overview of the space available on each file system.

**Options:**

\-h: Displays sizes in human-readable format (e.g., KB, MB, GB).

\-T: Displays the file system type along with disk usage.

**Examples:**

df -h # Displays disk space information for all mounted file systems

df -h /dev/sda1 # Displays disk space information for a specific file system

df -hT # Displays disk space information with file system types

## **ln - Create Links:**

The ln command is used to create hard links and symbolic links.

**Options:**

\-s: Creates a symbolic link instead of a hard link.

**Examples:**

ln /path/to/originalfile /path/to/hardlink # Creates a hard link

ln -s /path/to/originalfile /path/to/symlink # Creates a symbolic link

## **readlink - Display Symbolic Link Value:**

The readlink command is used to display the value of a symbolic link.

**Example:**

readlink /path/to/symlink # Display the target of the symbolic link

## **unlink - Remove Links:**

The unlink command is used to remove (delete) links. It can be used to remove both hard links and symbolic links.

**Example:**

unlink /path/to/link # Remove the link (whether hard link or symbolic link)

These Linux commands provide valuable insights into disk usage, allowing you to monitor storage capacity and identify potential space hogs. The ability to create and manage links efficiently helps organize files and directories and improve file system structure and accessibility.

## **6\. Additional Linux Commands**

## **1\. grep - Search Text:**

The grep command is used for pattern matching and searching text in files or standard input. It can search for a specific string or regular expression within files and display matching lines.

**Example:**

grep "pattern" filename

## **2\. find - Search for Files and Directories:**

The find command is used to search for files and directories based on various criteria such as name, size, type, and modification time. It is a powerful tool for locating specific files in a directory tree.

**Example:**

find /path/to/directory -name "\*.txt"

## **3\. top - Monitor System Activity:**

The top command displays real-time information about system activity, including CPU usage, memory usage, running processes, and more. It is useful for monitoring system performance and identifying resource-hungry processes.

**Example:**

top

## **4\. ps - Display Process Status:**

The ps command shows information about running processes on the system. It provides details such as process ID (PID), CPU and memory usage, parent process ID (PPID), and more.

**Example:**

ps aux

## **5\. kill - Terminate Processes:**

The kill command is used to send signals to processes, allowing you to terminate or control them. The default signal is SIGTERM, which terminates a process gracefully.

**Example:**

kill PID

## **6\. history - Display Command History:**

The history command shows a list of previously executed commands in the current session. It is useful for recalling and reusing commands without having to type them again.

**Example:**

history

## **7\. man - Display Manual Pages:**

The man command is used to display the manual pages (documentation) for various commands and system functions. It provides detailed information about command usage, options, and examples.

**Example:**

man ls

These additional Linux commands expand your control over the system, enabling you to search for text, monitor processes, manage running programs, and access useful documentation. They further enhance your experience and efficiency when working with Linux systems.

## **Reading Summary**

In this reading, you have learned the following:

-   File and directory commands
    
-   Linux commands for creating and deleting files and directories
    
-   Linux commands for copying and moving files and directories
    
-   Linux commands for permissions and ownership of a file or directory
    
-   Linux commands for disk usage and links




The solutions for the practice lab, along with the HTML file in module 2, can be accessed through the resource tab of the course. Please click on the below link, which will redirect you to the corresponding folder.

[https://www.coursera.org/learn/command-line-interface-and-scripting/resources/tEWFf](https://www.coursera.org/learn/command-line-interface-and-scripting/resources/tEWFf "Solutions Practice Labs - Week 2")





## **Reading Objective:**

In this reading, you will learn about open files and descriptor management services. You will also learn about the -memory file system structure in the Linux operating system. This reading will help you gain an understanding of file system layout in Linux operating systems. Finally, this reading will discuss the file system implementation in Linux and superblocks in Linux.

## **1\. Open Files and Descriptor Management Services**

## **Open Files and Descriptors:**

In Linux, an "open file" refers to a file or data stream that a process has opened during its execution. When a process opens a file, it is assigned a unique file descriptor, an integer value used to access the file during read and write operations. File descriptors are essential for managing file I/O in Linux.

## **File Descriptors Management:**

The Linux kernel uses a limited set of file descriptors for each process. By default, a process starts with three standard file descriptors:

0 (stdin): Standard input, typically used for reading input from the keyboard.

1 (stdout): Standard output, used for printing regular output.

2 (stderr): Standard error, used for printing error messages.

## **open() and close() System Calls:**

The open() system call is used to open files and create file descriptors. It returns a file descriptor that represents the opened file.

The close() system call is used to close file descriptors and release associated resources.

## **read() and write() System Calls:**

The read() system call reads data from an open file into a buffer provided by the process.

The write() system call writes data from a buffer provided by the process to an open file.

## **fcntl() System Call:**

The fcntl() system call is used for file descriptor manipulation. It can be used to change the properties of a file descriptor, such as setting it to be nonblocking or changing file access modes.

## **lsof - List Open Files:**

The lsof (list open files) command is used to display information about files currently open by processes. It provides details like file names, file descriptors, process IDs, and more.

**Example:**

lsof -c <process\_name>

lsof -u <user\_name>

## **File Descriptor Limits:**

Each process has a limit on the number of file descriptors it can open simultaneously. You can view and modify this limit using the ulimit command.

**Example:**

ulimit -n # Displays the current file descriptor limit

ulimit -n <new\_limit> # Sets a new file descriptor limit

## **dup() and dup2() System Calls:**

The dup() system call duplicates an existing file descriptor, creating a new one that refers to the same file or data stream.

The dup2() system call duplicates a file descriptor to a specified file descriptor number, allowing you to control the file descriptor value.

## **Importance of Descriptor Management:**

Proper management of file descriptors is critical to prevent resource leaks and ensure efficient use of system resources. Failing to close unused file descriptors can lead to performance issues and unnecessary resource consumption.

Understanding how file descriptors work and effectively managing them allows processes to interact with files and data streams efficiently and safely in a Linux environment.

## **2\. In-Memory File System Structure in Linux Operating System**

An in-memory file system (also known as tmpfs) is a file system that resides entirely in memory and does not use physical storage on disk. In Linux, tmpfs is a virtual file system that allows creating and accessing files and directories stored in RAM. It offers several benefits and use cases.

## **Characteristics of tmpfs:**

**Speed:** As it operates in memory, tmpfs provides fast read and write access, making it suitable for temporary data storage and processing.

**Volatility:** Since it resides in RAM, tmpfs is volatile. Data stored in tmpfs is lost when the system is shut down or when the tmpfs is unmounted.

## **Mounting tmpfs:**

Tmpfs can be mounted at any directory path just like other file systems. The mount command is used to mount tmpfs with specific options.

**Example:**

mount -t tmpfs -o size=1G tmpfs /mnt/tmpfs

## **Usage Scenarios:**

tmpfs is commonly used for temporary data storage, caching, and creating file systems for temporary purposes. Some typical use cases include:

**/tmp directory:** Linux distributions often use tmpfs to mount the /tmp directory, allowing temporary files to be stored in RAM.

**Caching:** It can be used to cache frequently accessed data, reducing read and write latency.

**Temporary file storage:** Tmpfs can serve as a temporary scratchpad for programs or during system maintenance.

## **Limitations:**

**Memory Limit:** Tmpfs uses system memory, so its size is limited by the amount of available RAM.

**Volatility:** As a volatile file system, any data stored in tmpfs will be lost if the system loses power or the tmpfs is unmounted.

**Swap Usage:** If RAM becomes scarce, tmpfs may use swap space on the disk, which can impact performance.

## **Cleaning tmpfs:**

Since tmpfs resides in memory and has limited capacity, it is essential to manage its content properly to avoid running out of memory. Unnecessary or large files in tmpfs should be periodically removed to free up memory.

**Example:**

rm -rf /mnt/tmpfs/\*

An in-memory file system (tmpfs) in Linux is a powerful tool for temporary data storage, caching, and managing files that need fast access. It offers speed and efficiency for certain use cases but requires careful consideration of memory usage and data volatility. Understanding tmpfs and its capabilities can help optimize file system design and improve system performance.

## **3\. File System Layout in Linux Operating Systems**

The file system layout in Linux refers to the organization and structure of directories, files, and other data within the file system. Linux follows a hierarchical directory structure, where directories are organized in a tree-like format. The root directory ("/") is the top-level directory from which all other directories and files originate.

## **1\. Root Directory ("/"):**

The root directory is the starting point of the file system hierarchy.

All other directories and files are organized under the root directory.

## **2\. Standard Directories:**

Linux systems have several standard directories with specific purposes:

-   /bin: Contains essential binary executable files, like basic shell commands (e.g., ls, cp, mv).
    
-   /sbin: Contains binary executable files used by the system administrator (e.g., ifconfig, fdisk).
    
-   /usr: Contains user-specific data and programs, including user binaries, libraries, documentation, and more.
    
-   /var: Holds variable data, such as log files, temporary files, mail spools, and printer spools.
    

## **3\. System Directories:**

-   /etc: Contains system configuration files.
    
-   /dev: Contains device files representing physical and virtual devices.
    
-   /proc: A virtual file system that provides information about running processes and system information.
    
-   /sys: A virtual file system that exposes kernel data structures and allows system configuration.
    

## **4\. Home Directory ("~"):**

Each user on the system has a home directory, represented by the tilde symbol "~" followed by the username.

It is the default directory for users when they log in and typically contains their personal files and configurations.

## **5\. Mount Points:**

Linux allows multiple file systems to be mounted at various locations in the directory hierarchy.

Mount points are directories where additional file systems are attached.

## **4\. File System Implementation in Linux**

The file system implementation in Linux refers to the way data is organized, stored, and accessed on physical storage devices (hard disks, SSDs, etc.). Linux supports various file system types, each with its implementation details. The most commonly used file systems in Linux are as follows.

## **1\. Ext4 (Fourth Extended File System):**

The default file system on many Linux distributions.

It offers support for large files and partitions, journaling for data consistency, and backward compatibility with older ext file systems.

## **2\. XFS (X File System):**

A high-performance file system designed for scalability and reliability.

Suitable for large storage systems and parallel I/O operations.

## **3\. Btrfs (B-tree File System):**

A modern, feature-rich file system that supports features like snapshots, subvolumes, and data compression.

Provides improved data integrity and fault tolerance.

## **4\. ZFS (Zettabyte File System):**

Though not a native Linux file system, ZFS is widely used for its robustness and data protection capabilities.

It combines file system and logical volume management functionalities.

## **5\. Others:**

Linux supports various other file systems like FAT32, NTFS (for compatibility with Windows), and more.

Understanding the file system layout and implementation in Linux is essential for effective file organization, storage management, and system performance. It allows users and system administrators to efficiently navigate the directory structure, manage files, and choose appropriate file systems based on their specific requirements.

## **5\. Superblocks in Linux**

In Linux, the superblock is a crucial data structure that defines the overall characteristics and organization of a file system. It is the first data block of the file system and is usually located at a fixed offset from the beginning of the disk partition or file system.

## **Key Information in the Superblock:**

The superblock contains essential metadata about the file system, including:

-   **File system type:** Indicates the type of file system, such as ext4, XFS, btrfs, etc.
    
-   **Total inodes:** The number of inodes (data structures representing files and directories) in the file system.
    
-   **Total data blocks:** The number of data blocks available for storing file data.
    
-   **Block size:** The size of each data block in bytes.
    
-   **Mount count:** The number of times the file system has been mounted since its last check.
    
-   **Mount time and last write time:** Timestamps of when the file system was last mounted and last written to.
    
-   **Inode and block bitmaps:** Bitmaps indicate which inodes and data blocks are in use.
    

## **Backup Superblocks:**

In addition to the primary superblock, Linux file systems often have backup copies of the superblock distributed throughout the file system. These backups serve as redundancy to recover the file system if the primary superblock gets corrupted.

## **Role of Superblocks during File System Mount:**

When a file system is mounted, the kernel reads the superblock to gather crucial information about the file system's layout, size, and health. It uses this information to correctly interpret the file system's contents and enable access to files and directories.

## **Superblock Corruption and Recovery:**

If the primary superblock is damaged due to hardware failure or other issues, Linux can use the backup superblocks to recover the file system. The fsck (file system check) command can be used to scan for and repair file system inconsistencies, including superblock issues.

## **Accessing Superblock Information:**

System administrators and advanced users can access superblock information using specialized tools or by reading the raw disk data (with caution). The dumpe2fs command is commonly used to display detailed superblock information for ext2, ext3, and ext4 file systems.

**Example:**

dumpe2fs /dev/sda1

**Note:** Modifying superblock data directly is risky and can lead to data loss or file system corruption. It is recommended to rely on standard commands and utilities for file system management.

The superblock is a critical data structure in Linux file systems, containing vital metadata about the file system's layout, size, and organization. Understanding superblocks helps system administrators diagnose and recover from file system-related issues, ensuring the stability and reliability of the file system.

## **Reading Summary**

In this reading, you have learned the following:

-   Open files and descriptor management services
    
-   In-memory file system structure in Linux operating system
    
-   File system layout in Linux operating systems
    
-   File system implementation in Linux
    
-   Superblocks in Linux


## **Reading Objective:**

In this reading, you will learn about the conversion of a path name to an inode system. You will also learn about the assignment and freeing of data blocks and inodes in Linux operating systems. The reading will help you gain an understanding of the complete data structure for inode in Linux file system. Finally, this reading will help you explore the options in a Link in the Linux operating system.

## **1\. Conversion of a Path Name to an inode**

In Linux, the file system uses inodes to represent files and directories. An inode (index node) is a data structure that stores metadata about a file, such as its permissions, ownership, timestamps, and most importantly, the physical location of the file's data blocks on the disk. Each file and directory in a Linux file system is associated with a unique inode number.

When a file path is provided, the Linux file system needs to traverse the directory hierarchy to locate the corresponding inode for the file or directory specified in the path. The process of converting a path into an inode involves following the directory entries in each component of the path until the final inode is reached.

Let's walk through an example of how the Linux file system converts a path into an inode:

Suppose we have the following directory structure:

/

└── home

└── user

├── documents

│ └── file1.txt

└── downloads

└── file2.txt

Assume the root directory ("/") has an inode number of 1.

**Start at the root ("/"):** The path we want to resolve is "/home/user/documents/file1.txt".

**Tokenize the path:** The path is split into individual components or tokens: \["home," "user," "documents," "file1.txt"\].

**Traverse the path:** Starting from the root inode (inode 1), the file system follows the directory entries to reach the desired inode. For each component of the path:

a. "home" component:

The file system looks for the entry "home" in the root directory (inode 1). It finds the inode number associated with "home" (let's say inode 10).

b. "user" component:

The file system looks for the entry "user" in the "home" directory (inode 10). It finds the inode number associated with "user" (let's say inode 20).

c. "documents" component:

The file system looks for the entry "documents" in the "user" directory (inode 20). It finds the inode number associated with "documents" (let's say inode 30).

d. "file1.txt" component:

The file system looks for the entry "file1.txt" in the "documents" directory (inode 30). It finds the inode number associated with "file1.txt" (let's say inode 40).

## **Path resolved:**

The file system has now reached the inode (inode 40) associated with "file1.txt." The path has been successfully converted into an inode.

## **Access file data:**

At this point, the file system can use the inode (inode 40) to access the file's metadata (permissions, timestamps, etc.) and read the data blocks associated with "file1.txt" to access its content.

## **2\. Assignment and Freeing of Data Blocks and inodes in Linux Operating Systems**

In Linux, data blocks and inodes are crucial elements of the file system. Data blocks store the actual file data, while inodes store metadata about files and directories. Proper assignment and freeing of data blocks and inodes are essential for efficient file system management and to avoid issues like data corruption and storage depletion.

## **Assignment of data blocks and inodes:**

a. Data blocks:

Data blocks are allocated to files to store their content.

Linux file systems use different allocation strategies, such as block allocation maps and extent-based allocation, to efficiently manage data blocks.

b. Inodes:

Each file and directory in the file system is represented by an inode, which contains metadata about the file, such as permissions, timestamps, size, and pointers to data blocks.

Inodes are dynamically assigned to new files and directories when they are created.

## **Freeing of data blocks and inodes:**

a. Data blocks:

When a file or directory is deleted, its data blocks are marked as free and can be reused for new files.

The unlink command is used to remove a file, and the data blocks associated with the file are freed.

**Example:**

unlink filename

b. Inodes:

When a file or directory is deleted, its inode is marked as free and can be reused for new files or directories.

The rm command is used to remove a file or directory, and its inode is freed.

**Example:**

rm filename

rmdir directory

## **df Command:**

The df command is used to display file system disk space usage, including the number of used and available inodes.

**Example:**

df -i

## **debugfs Command:**

The debugfs command provides a powerful interface to interact with the file system's internal structures, including data blocks and inodes. It can be used for advanced tasks and debugging.

**Example (Displaying Inode Information):**

debugfs -R 'stat <inode\_number>' /dev/sda1

## **Monitoring disk usage:**

Regularly monitoring disk usage and available inodes is essential to prevent running out of storage or inodes, which can cause file creation failures.

**Example:**

watch df -i

Proper management of data blocks and inodes ensures efficient use of storage and prevents file system issues.

Deleting files or directories releases their associated data blocks and inodes for reuse.

Continuous monitoring of disk space and inodes helps maintain a healthy file system. Understanding the assignment and freeing of data blocks and inodes in Linux enables users to manage file systems effectively and ensure optimal utilization of storage resources. It also helps maintain a stable and reliable file system environment.

## **3\. Complete Data Structure for Inode in Linux File System**

In Linux file systems, the inode (index node) is a fundamental data structure that represents each file or directory. It stores crucial metadata about the file, enabling the operating system to efficiently manage and access the file's data and attributes. The complete data structure for an inode in a typical Linux file system consists of the following fields:

## **1\. File mode (permissions):**

Indicates the file type and access permissions.

It consists of 12 bits representing the file type and three sets of 3 bits each for the read, write, and execute permissions for the owner, group, and others, respectively.

## **2\. Owner and group IDs:**

Store the numeric user ID (UID) of the file's owner and the numeric group ID (GID) of the file's group.

## **3\. File size:**

Stores the size of the file in bytes.

## **4\. Timestamps:**

Three timestamps indicating various time-related information about the file:

**Access time (atime):** The last time the file was accessed (read).

**Modification time (mtime):** The last time the file's content was modified (written).

**Change time (ctime):** The last time the file's inode information was changed (e.g., permissions modified).

## **5\. Number of links:**

Keeps track of the number of hard links to the inode.

When a file is linked (hard-linked) to multiple locations, they all share the same inode.

## **6\. Blocks pointers:**

Pointers to data blocks that store the file's actual content.

The number of block pointers may vary based on the file system and file size.

For small files, direct block pointers are used (e.g., 12 pointers).

For larger files, indirect block pointers (e.g., single, double, triple indirect) are used to access additional data blocks.

## **7\. Extended attributes and flags:**

Additional file attributes and flags that provide extra information or control over the file.

Examples include extended file permissions, file compression, and immutable flags.

## **8\. Generation number:**

A unique identifier for the inode that helps prevent accidental reuse of the inode number.

## **9\. File system specific data:**

Space reserved for file system-specific data or extensions.

## **10\. Access control lists (ACLs) and security context:**

For file systems that support extended access control mechanisms (e.g., POSIX ACLs), the inode may contain pointers to ACL entries and security context information.

It's important to note that the inode structure may vary slightly depending on the file system type (e.g., ext4, XFS, btrfs) and its capabilities. Each file system may add its specific fields to the inode structure to support advanced features and optimizations.

Understanding the complete data structure for the inode allows Linux file systems to efficiently manage files and directories, handle permissions, track file sizes, and store essential metadata. This data structure is vital to maintain the integrity and performance of the file system.

## **4\. Exploring the Options in a Link in Linux Operating Systems**

In Linux, links are used to create references to files or directories, allowing them to be accessed from multiple locations within the file system. There are two types of links: hard links and symbolic links (symlinks). Exploring the options in a link involves understanding the attributes and characteristics of these links, as well as the different functionalities they offer.

## **1\. Hard links:**

A hard link is a direct reference to the inode of a file. Multiple hard links point to the same inode, and the file is considered to have multiple names or paths.

Changes made to one hard link are reflected in all other hard links since they share the same inode.

Hard links can only be created for files (not directories) and cannot reference files on different file systems.

Options for Hard Links:

Hard links do not have many options. They simply inherit the attributes and permissions of the original file. Changes made to the original file are automatically applied to all hard links.

## **2\. Symbolic links (Symlinks):**

A symbolic link (or symlink) is a separate file that contains the path to the target file or directory. It acts as a pointer to the target location.

Symlinks can point to files or directories on different file systems, including non-existent locations.

**Options for symbolic links:**

Symlinks have some options and behaviors that can be explored:

\-s (Symbolic): This option is used when creating a symlink to indicate that it is a symbolic link.

It is usually used with the ln command: ln -s target link\_name.

Relative and absolute paths: Symlinks can use either relative or absolute paths to reference the target. A relative path points to the target from the symlink's location, while an absolute path specifies the full path to the target.

Broken Symlinks: If a symlink points to a nonexistent target, it is referred to as a broken symlink. These are commonly encountered during system maintenance and need to be handled appropriately.

## **3\. ls Command:**

The ls command with the -l option can be used to explore information about links and their targets. It provides details such as permissions, owner, group, size, timestamps, and whether a file is a symlink.

**Example:**

ls -l /path/to/symlink

## **4\. readlink Command:**

The readlink command is used to read the value (target) of a symlink.

**Example:**

readlink /path/to/symlink

## **5\. file Command:**

The file command is used to determine the type of a file, including whether it is a symlink.

**Example:**

file /path/to/file\_or\_symlink

Understanding the options and attributes of links in Linux allows users to create, manage, and explore link relationships effectively. Hard links provide direct references to files, while symbolic links act as pointers to files or directories, offering versatile ways to organize and access data within the file system..

## **Reading Summary**

In this reading, you have learned the following:

-   Conversion of a path name to an inode
    
-   Assignment and freeing of data blocks and inodes in Linux operating systems
    
-   Complete data structure for inode in Linux file system
    
-   Exploring the options in a link in Linux operating systems





The solutions for the practice lab, along with the HTML file in module 3, can be accessed through the resource tab of the course. Please click on the below link, which will redirect you to the corresponding folder.

[https://www.coursera.org/learn/command-line-interface-and-scripting/resources/1ukTi](https://www.coursera.org/learn/command-line-interface-and-scripting/resources/1ukTi "Solutions Practice Labs - Week 3")



## **Reading Objective:**

In this reading, you will learn about kernel I/O structure and the block and character devices. This reading will introduce you to device drivers in Linux operating systems, I/O queuing, and interrupt handling in Linux. Finally, this reading will help you inspect hard disks and sectors in Linux operating systems.

## **I/O in Linux: Kernel I/O Structure**

## **What Is I/O?**

Input/output (I/O) refers to the process of transferring data between a computer’s internal memory \[central processing unit (CPU), RAM\] and external devices like disks, network interfaces, keyboards, and displays. Input involves receiving data from external sources, whereas output involves sending data to external destinations.

## **I/O in Linux:**

In Linux, I/O is essential for communication between user processes, the kernel, and hardware devices. The Linux kernel provides various interfaces and mechanisms to handle I/O efficiently. Understanding the I/O subsystem is crucial for optimizing system performance and writing efficient applications.

## **Kernel I/O Structure:**

The Linux kernel I/O structure consists of three main layers:

**Block I/O Layer:**

The block I/O layer is responsible for managing block devices, such as hard drives, solid-state drives (SSDs), USB drives, and other storage media. Block devices store data in fixed-size blocks, typically ranging from 512 B to 4 kB. The key components of the block I/O layer include:

_**Block Device Drivers:**_ These are kernel modules that provide the interface between the kernel and specific block devices. They manage I/O requests and handle communication with the hardware. Examples include the SATA, SCSI, and NVMe drivers.

_**I/O Scheduler:**_ The I/O scheduler is responsible for optimizing the order in which I/O requests are executed to minimize disk seek times and improve overall I/O performance. Popular Linux I/O schedulers include completely fair queuing (CFQ), NOOP, and Deadline.

_**Buffer Cache:**_ The buffer cache is a region of the RAM used to cache data read from and write to block devices. Caching improves performance by reducing the number of actual disk accesses, especially for frequently accessed data.

**Character I/O Layer:**

The character I/O layer manages character devices, which transfer data character by character. Character devices include devices like keyboards, mouses, terminals, and serial ports. Key components of the character I/O layer include:

_**Character Device Drivers:**_ These drivers handle communication with specific character devices. For example, the TTY driver manages terminal devices (e.g., /dev/tty1).

**Network Layer:**

The Network Layer deals with I/O operations related to network communication. It manages data transfer in the form of packets between the computer and network devices. Key components of the network layer include:

_**Network Device Drivers:**_ These drivers handle communication with network interfaces, such as Ethernet cards and Wi-Fi adapters.

_**Network Stack:**_ The network stack manages the routing, flow control, and transmission of network packets. It includes components like the IP layer (IPv4 and IPv6), transport layer (TCP, UDP), and socket interface.

**sysfs and procfs:** Linux provides special filesystems, that is, sysfs (system file system) and procfs (process file system), to expose kernel information and configuration to user space. These filesystems enable users and system administrators to interact with kernel I/O settings and parameters using standard file I/O operations.

## **Kernel APIs:**

The Linux kernel provides a set of application programming interfaces (APIs) that allow user-space processes to interact with the kernel and perform I/O operations. Some commonly used kernel I/O APIs include read(), write(), open(), ioctl(), and mmap().

**Examples of I/O in Linux:**

**Reading/Writing a File:**

#include <stdio.h>

int main() {

FILE \*file = fopen("example.txt", "r"); // Open file in read mode

if (file != NULL) {

char buffer\[100\];

while (fgets(buffer, sizeof(buffer), file) != NULL) {

// Process data in the buffer

printf("%s", buffer);

}

fclose(file);

}

return 0;

}

In this example, the program reads a file named "example.txt" line by line using the fgets() function and prints its content on the screen.

## **Using I/O Redirection:**

In Linux, you can redirect standard input, output, and error streams to/from files using the following symbols:

\>: redirects standard output to a file.

<: redirects standard input from a file.

2>: redirects standard error to a file.

**Example:**

$ echo "Hello, I/O" > output.txt # Redirects output to a file

$ cat < input.txt # Redirects input from a file

$ ls non\_existent\_file 2> error.txt # Redirects error to a file

## **Interacting with Devices:**

Linux treats devices as special files in the /dev/ directory.

For instance:

/dev/sda: represents the first hard disk.

/dev/keyboard: represents the keyboard.

## **Commands Related to Kernel I/O and I/O Devices:**

lsblk: lists block devices (displays information about block devices and their partitions).

lspci: lists peripheral component interconnect (PCI) devices (displays information about devices connected via the PCI bus).

lsusb: lists USB devices (displays information about devices connected via USB).

lsmod: lists loaded kernel modules (displays a list of currently loaded kernel modules).

modprobe: loads kernel modules (loads a kernel module into the running kernel).

rmmod: removes kernel modules (unloads a kernel module from the running kernel).

dmesg: displays kernel messages (displays the kernel ring buffer and boot messages).

## **I/O Devices: Block and Character Devices**

## **Introduction to I/O Devices:**

I/O devices in a computer system are external peripherals that facilitate data exchange between the CPU and the outside world. Linux classifies I/O devices into two main categories: block devices and character devices. Each type has unique characteristics and usage patterns in the Linux environment.

## **Block Devices:**

Block devices are I/O devices that transfer data in fixed-size blocks, typically ranging from 512 B to 4 kB. They include storage devices like hard disk drives, SSDs, USB drives, and redundant array of independent disks (RAID). Block devices are treated as a sequence of blocks, and data is read or written in block-sized chunks.

**Characteristics of Block Devices:**

Data is accessed in fixed-size blocks.

Random access is possible (reading/writing any block at any time).

Suitable for file systems and applications that require block-level access.

They have a specific capacity for storing data.

**Examples: /dev/sda (hard disk)** and **/dev/nvme0n1 (NVMe SSD).**

**Examples of Block Device Usage:**

_**Mounting File Systems:**_ When you mount a file system in Linux, it interacts with the underlying block device where the data is stored.

**Example:**

$ mount /dev/sda1 /mnt/mydrive

_**Partitioning:**_ Partitioning involves dividing a block device into multiple logical sections to organize data efficiently.

**Example (using fdisk):**

$ sudo fdisk /dev/sda

## **Character Devices:**

Character devices are I/O devices that transfer data character by character or byte by byte. They include devices such as keyboards, mouses, serial ports, terminals, and audio devices. Unlike block devices, character devices do not have fixed-size blocks, and data is accessed as a stream of characters or bytes.

**Characteristics of Character Devices:**

Data is accessed in individual characters or bytes.

Sequential access is typical (reading/writing sequentially from the beginning).

Suitable for real-time data transmission and interactive applications.

They usually do not have a fixed capacity for storing data.

**Examples:** /dev/tty (terminal) and /dev/ttyS0 (serial port).

**Examples of Character Device Usage:**

_**Reading Input from Keyboard:**_ When you type on the keyboard, the characters are read from the character device representing the keyboard.

**Example (reading from the terminal):**

#include <stdio.h>

int main() {

char buffer\[100\];

fgets(buffer, sizeof(buffer), stdin); // Read input from stdin (character device)

printf("You entered: %s\\n", buffer);

return 0;

}

_**Sending Data to a Serial Port:**_ When communicating with external devices over a serial port, data is written to the character device representing the serial port.

**Example (using write() system call):**

#include <fcntl.h>

#include <unistd.h>

int main() {

int fd = open("/dev/ttyS0", O\_WRONLY); // Open the character device for //writing

if (fd != -1) {

write(fd, "Hello, Serial!", 14); // Write data to the serial port

close(fd); // Close the file descriptor

}

return 0;

}

## **Commands Related to Block Devices:**

mount: mounts a file system (mounts a block device to a specific mount point).

umount: unmounts a file system (unmounts a mounted block device).

fdisk: partition table manipulator (used for creating and managing disk partitions).

## **Commands Related to Character Devices:**

cat: concatenates and displays file content (can be used to read from character devices).

echo: outputs data to the terminal (can be used to write to character devices).

stty: changes and prints terminal line settings (can be used to configure character devices like serial ports).

## **Device Drivers in Linux Operating Systems**

## **Introduction to Device Drivers:**

Device drivers are software components that act as intermediaries between the hardware devices and the operating system. They enable the operating system to communicate and control various hardware peripherals, such as graphics cards, network adapters, USB devices, and storage devices. In Linux, device drivers play a critical role in ensuring the efficient and proper functioning of hardware devices.

## **Types of Device Drivers in Linux:**

Linux supports two main types of device drivers:

_**Kernel Space Device Drivers:**_ These drivers are directly integrated into the Linux kernel. They have direct access to kernel resources and can interact with hardware at a lower level. Kernel space drivers are generally preferred for critical and performance-sensitive tasks.

_**User Space Device Drivers:**_ These drivers run in user space outside the kernel. They interact with the hardware using system calls and kernel interfaces. User-space drivers are more flexible and can be loaded and unloaded dynamically, but they may incur some performance overhead due to the user-kernel boundary crossing.

Device drivers are essential components in Linux that enable communication between the operating system and hardware devices. They play a vital role in managing various peripherals and ensuring the smooth functioning of a Linux system. Writing device drivers requires an understanding of the Linux kernel interfaces and the specific hardware being targeted. Properly implemented device drivers can significantly enhance the performance and stability of the overall system.

## **Commands Related to Device Drivers:**

lsmod: lists loaded kernel modules (displays a list of currently loaded kernel modules).

modinfo: shows information about a kernel module (displays information about a specific module).

insmod: inserts a module into the kernel (loads a kernel module into the running kernel).

rmmod: removes kernel modules (unloads a kernel module from the running kernel).

ls /dev: lists device files in the /dev directory (shows various device files, including block and character devices).

## **I/O Queuing and Interrupt Handling in Linux**

## **Introduction to I/O Queuing:**

I/O queuing is a critical mechanism in the Linux kernel that optimizes the handling of I/O requests from multiple processes and devices. It enables efficient scheduling and execution of I/O operations, reducing latency and improving system performance.

## **I/O Scheduling Algorithms:**

In Linux, the I/O scheduler is responsible for managing the order in which pending I/O requests are serviced. Different I/O scheduling algorithms are available, and the choice of scheduler can impact system performance depending on the workload and disk characteristics. Some common I/O scheduling algorithms in Linux include:

**Completely Fair Queuing (CFQ):** provides a fair distribution of I/O bandwidth among processes, suitable for desktop and interactive workloads.

**Deadline:** guarantees time-bound I/O requests to improve responsiveness for real-time tasks.

**NOOP:** simple First In, First Out (FIFO)-based scheduler with minimal overhead, best suited for SSDs and devices with low latency.

**Example: Changing I/O Scheduler:**

You can change the I/O scheduler for a specific block device using the iosched file in the /sys filesystem.

\# Check the current scheduler for the device (e.g., /dev/sda)

$ cat /sys/block/sda/queue/scheduler

\# Change the scheduler to CFQ

$ echo cfq > /sys/block/sda/queue/scheduler

\# Change the scheduler to deadline

$ echo deadline > /sys/block/sda/queue/scheduler

\# Change the scheduler to NOOP

$ echo noop > /sys/block/sda/queue/scheduler

## **Interrupt Handling in Linux:**

Interrupt handling is a fundamental aspect of operating systems, including Linux. When a hardware device requires attention, it raises an interrupt signal to the CPU, indicating that it needs immediate processing. Interrupt handling ensures timely response to hardware events without consuming excessive CPU resources.

## **Interrupt Handlers in Linux:**

In Linux, interrupt handling is managed by interrupt handlers, also known as interrupt service routines. Each hardware device typically has its corresponding interrupt handler registered with the kernel.

**Example: Writing an Interrupt Handler:**

Below is a simplified example of an interrupt handler for a fictional device that generates an interrupt when a button is pressed.

#include <linux/interrupt.h>

#define BUTTON\_IRQ 42

irqreturn\_t button\_interrupt\_handler(int irq, void \*dev\_id) {

// Perform necessary actions when the button is pressed

printk(KERN\_INFO "Button Pressed!\\n");

return IRQ\_HANDLED;

}

static int \_\_init init\_button\_device(void) {

int result;

// Request the IRQ line for the button

result = request\_irq(BUTTON\_IRQ, button\_interrupt\_handler, IRQF\_TRIGGER\_FALLING, "button\_device", NULL);

if (result) {

printk(KERN\_ERR "Failed to request IRQ %d\\n", BUTTON\_IRQ);

return result;

}

printk(KERN\_INFO "Button Device Initialized\\n");

return 0;

}

static void \_\_exit exit\_button\_device(void) {

// Free the IRQ line for the button

free\_irq(BUTTON\_IRQ, NULL);

printk(KERN\_INFO "Button Device Unloaded\\n");

}

module\_init(init\_button\_device);

module\_exit(exit\_button\_device);

MODULE\_LICENSE("GPL");

## **Commands Related to I/O Queuing and Interrupt Handling:**

cat /sys/block/<device>/queue/scheduler: checks the current I/O scheduler for a block device.

echo <scheduler> > /sys/block/<device>/queue/scheduler: changes the I/O scheduler for a block device.

cat /proc/interrupts: displays interrupt statistics (shows the number of interrupts handled by each CPU).

Please note that some of these commands may require root (administrative) privileges to execute. Always exercise caution while using commands that interact with the kernel and device drivers, as improper use may lead to system instability or data loss.

## **Inspecting Hard Disks and Sectors in Linux Operating Systems**

## **Introduction:**

Inspecting hard disks and sectors in a Linux operating system is crucial for understanding the storage configuration and disk health and analyzing disk-related issues. Linux provides several commands and utilities to examine hard disks, partitions, and sectors, helping users and system administrators make informed decisions regarding storage management and troubleshooting.

## **View Disk Information:**

The following commands can be used to view general information about hard disks in Linux:

lsblk: lists block devices, their mount points, and other details like size and partitions.

fdisk -l: displays partition information for all detected disks.

parted -l: shows detailed partition information using GNU Parted.

df -h: displays the disk space usage of mounted file systems.

## **SMART (Self-Monitoring, Analysis, and Reporting Technology):**

SMART is a monitoring system used to check the health and reliability of hard drives. The smartctl command is used to access SMART data and perform tests:

smartctl -a /dev/sdX: shows the SMART attributes of the specified hard disk (e.g., /dev/sda).

smartctl -t long /dev/sdX: initiates a long SMART self-test on the hard disk.

## **Inspect Disk Partitions:**

You can examine and manipulate disk partitions using the following commands:

fdisk /dev/sdX: interactively manages disk partitions (replace X with the appropriate disk identifier).

gdisk /dev/sdX: interactive GUID partition table (GPT) manipulator.

## **Low-Level Disk Inspection:**

dd is a versatile utility to read or write data at the block level. Exercise caution while using these commands as they can irreversibly overwrite data:

dd if=/dev/sdX of=/path/to/output\_file: creates an image (backup) of the entire disk (replace X with the disk identifier).

dd if=/dev/zero of=/dev/sdX bs=1M count=1: writes zeros to the first 1 MB of the disk.

## **Reading Disk Sectors:**

Linux provides access to raw disk sectors using the dd command:

dd if=/dev/sdX of=/path/to/output\_file bs=512 count=1 skip=N: reads the Nth sector of the disk (replace X with the disk identifier).

Inspecting hard disks and sectors in a Linux operating system is essential for managing storage, understanding disk health, and diagnosing storage-related issues. With the provided commands and utilities, users and system administrators can gain valuable insights into the storage configuration and ensure the reliability and performance of their storage devices. Always exercise caution when performing low-level operations on disks to prevent data loss or unintended consequences.

**Examples:**

View Disk Information:

\# List block devices

$ lsblk

\# Display partition information for all disks

$ sudo fdisk -l

\# Show detailed partition information using GNU Parted

$ sudo parted -l

\# Display disk space usage of mounted file systems

$ df -h

## **SMART (Self-Monitoring, Analysis, and Reporting Technology):**

\# Show the SMART attributes of the specified hard disk (e.g., /dev/sda)

$ sudo smartctl -a /dev/sda

\# Perform a long SMART self-test on the hard disk

$ sudo smartctl -t long /dev/sda

## Inspect Disk Partitions:

\# Interactively manage disk partitions for /dev/sda (use 'd' to delete, 'n' to create, 'p' for primary, 'w' to save)

$ sudo fdisk /dev/sda

\# Interactive GUID partition table (GPT) manipulator for /dev/sda (use 'd' to delete, 'n' to create, 'w' to save)

$ sudo gdisk /dev/sda

## Low-Level Disk Inspection:

\# Create an image (backup) of the entire /dev/sda disk

$ sudo dd if=/dev/sda of=/path/to/output\_file.img

\# Write zeros to the first 1 MB of /dev/sda (use with caution, as it overwrites data)

$ sudo dd if=/dev/zero of=/dev/sda bs=1M count=1

## Reading Disk Sectors:

\# Read the first sector of /dev/sda and save it to the output\_file

$ sudo dd if=/dev/sda of=/path/to/output\_file bs=512 count=1 skip=0

Please note that some of these commands require superuser privileges (sudo) to execute, as they deal with low-level disk operations. Always exercise caution while using commands that involve reading or writing data at the block level, as they can cause data loss if not used correctly. Double-check the disk identifiers (/dev/sdX) before running any commands, and ensure you have a good understanding of the implications of each command before using them.

## **Reading Summary**

In this reading, you have learned the following:

-   I/O in Linux: kernel I/O structure
    
-   I/O devices**:** block and character devices
    
-   Device drivers in Linux operating systems
    
-   I/O queuing and interrupt handling in Linux
    
-   Inspecting hard disks and sectors in Linux operating systems




## **Reading Objective:**

In this reading, you will learn about various commands, such as “lsblk” which lists block devices, “fdisk” which manipulates disk partitions, and “df” which displays information about the disk space. This reading will also introduce you to the Linux commands, such as hwinfo, parted, cfdisk, sfdisk, and smartctl Linux commands. Finally, this reading will help you apply the command line tool to check the health of a disk drive on a Linux system.

## **lsblk, fdisk, and df Commands**

## **1\. lsblk: List Block Devices**

The lsblk command is used to display information about block devices (storage devices like hard drives, SSDs, etc.) and their attributes.

**Syntax:**

lsblk \[options\] \[device...\]

**Examples:**

List all block devices:

lsblk

List block devices with filesystem and mount point information:

lsblk -f

Show only specific columns:

lsblk -o NAME,SIZE,MOUNTPOINT

Display the tree view of block devices:

lsblk -t

## **2\. fdisk: Manipulate Disk Partitions**

The fdisk command is used to create, modify, or delete disk partitions on block devices.

**Syntax:**

fdisk \[options\] device

**Examples:**

Start fdisk on a device (e.g., /dev/sda):

fdisk /dev/sda

Print existing partitions:

p

Create a new partition:

n

Delete a partition:

d

Write changes and exit:

w

## **3\. df: Disk Space Usage**

The df command displays information about the disk space usage of filesystems.

**Syntax:**

df \[options\] \[file...\]

**Examples:**

Show disk space usage of all mounted filesystems:

df -h

Display usage for a specific filesystem:

df -h /dev/sda1

Show disk space usage with human-readable sizes:

df -h

Display usage in 1K blocks:

df -k

**Note:** Make sure to use these commands with caution, especially fdisk, as modifying disk partitions can result in data loss.

The lsblk, fdisk, and df commands are powerful tools for managing and inspecting block devices, manipulating disk partitions, and monitoring disk space usage on Linux systems. Understanding how to use these commands can help you effectively manage your storage resources. Always exercise caution and double-check commands before applying changes to your system.

## **hwinfo and parted Linux Commands**

## **1\. hwinfo: Hardware Information**

The hwinfo command is used to gather detailed hardware information about your system.

**Syntax:**

hwinfo \[options\]

**Examples:**

Display complete hardware information:

hwinfo

Show specific hardware category (e.g., CPU, memory, and network):

hwinfo --cpu

Save hardware information to a file:

hwinfo --all > hardware\_info.txt

## **2\. parted: Disk Partitioning**

The parted command is a powerful utility for creating, resizing, and managing disk partitions.

**Syntax:**

parted \[options\] device

**Examples:**

Start parted on a device (e.g., /dev/sdb):

parted /dev/sdb

Create a new partition table (e.g., GPT):

mklabel gpt

Create a new partition:

mkpart primary ext4 0% 50%

Resize a partition:

resizepart 1 80%

Set partition flag (e.g., bootable):

set 1 boot on

Quit parted after making changes:

quit

**Note:** Both hwinfo and parted commands require superuser privileges (sudo) to access hardware information and manipulate disk partitions effectively.

The hwinfo and parted commands provide crucial capabilities for understanding your system’s hardware and managing disk partitions. hwinfo allows you to gather comprehensive hardware information, whereas parted empowers you to create, modify, and manage disk partitions efficiently. Proper usage of these commands can aid in system administration and troubleshooting tasks. Always use these commands with care, as they deal with low-level system components.

## **cfdisk, sfdisk, and smartctl Linux Commands**

## **1\. cfdisk: Console-Based Disk Partitioning**

The cfdisk command is a user-friendly console-based tool for creating, modifying, and managing disk partitions.

**Syntax:**

cfdisk device

**Examples:**

Start cfdisk on a device (e.g., /dev/sdb):

cfdisk /dev/sdb

Create a new partition:

New -> Enter partition size -> Select partition type

Delete a partition:

Select partition -> Delete

Write changes and exit:

Write -> Yes

## **2\. sfdisk: Scriptable Disk Partitioning**

The sfdisk command is used for scripting disk partitioning operations and creating partitions programmatically.

**Syntax:**

sfdisk \[options\] device

**Examples:**

Create partitions using a script file:

sfdisk /dev/sdb < partition\_script.txt

Print partition table to a file:

sfdisk -d /dev/sdb > partition\_table.txt

## **3\. smartctl: SMART Monitoring and Control**

The smartctl command is used to monitor and control the Self-Monitoring, Analysis, and Reporting Technology (SMART) attributes of storage devices.

**Syntax:**

smartctl \[options\] device

**Examples:**

Display SMART information for a device (e.g., /dev/sda):

smartctl -a /dev/sda

Short self-test on a device:

smartctl -t short /dev/sda

Check test results:

smartctl -l selftest /dev/sda

**Note:** SMART attributes provide insights into the health of storage devices and can help predict potential failures.

The cfdisk, sfdisk, and smartctl commands offer various capabilities for disk partitioning and storage device management. cfdisk provides an interactive console-based interface, sfdisk is used for scripted partitioning operations, and smartctl allows you to monitor the health of storage devices. Proper usage of these commands is essential to manage storage resources effectively and ensure the reliability of your system’s storage devices. Always exercise caution when performing operations that involve disk partitions and storage devices.

## **Command Line Tool to Check the Health of a Disk Drive on a Linux System**

## **Introduction:**

The health of a disk drive is crucial for ensuring the reliability and performance of a Linux system. The smartmontools package provides a command-line interface to interact with the SMART system built into most modern hard drives and solid-state drives. It allows you to check and monitor the health and attributes of your disk drives.

## **Installing smartmontools:**

You can install smartmontools using your distribution’s package manager. For example, on Debian/Ubuntu-based systems:

sudo apt-get install smartmontools

## Using smartmontools:

To check the health of a disk drive, use the smartctl command from the smartmontools package.

**Syntax:**

smartctl \[options\] device

**Examples:**

**Display Basic Disk Information:**

smartctl -i /dev/sda

This command provides general information about the disk, including its model, serial number, and firmware version.

**View Comprehensive SMART Data:**

smartctl -a /dev/sda

This command displays a detailed report of SMART attributes, error logs, and self-test results for the specified device.

**Run Short Self-Test:**

smartctl -t short /dev/sda

Initiates a short self-test on the device. You can check the test results later.

**Check Self-Test Log:**

smartctl -l selftest /dev/sda

This command displays the results of the self-tests that have been performed on the device.

**Long Self-Test:**

smartctl -t long /dev/sda

Initiates a more thorough long self-test on the device.

**Check Disk Temperature:**

smartctl -A /dev/sda | grep Temperature

This command retrieves the disk temperature information from the SMART data.

## **Interpreting Results:**

SMART attributes provide insights into the health of the disk drive. Attributes with non-zero values or increasing values might indicate potential issues. You can find more information about specific attributes in the drive’s documentation or online resources.

Using smartmontools and the smartctl command, you can proactively monitor the health of your disk drives, identify potential problems early, and take appropriate actions to prevent data loss and system downtime. Regularly checking and interpreting SMART data can contribute to maintaining a stable and reliable Linux system.

## **Reading Summary**

In this reading, you have learned the following:

-   lsblk, fdisk, and df commands
    
-   hwinfo and parted Linux commands
    
-   cfdisk, sfdisk, and smartctl Linux commands
    
-   Command line tool to check the health of a disk drive on a Linux system.




The solutions for the practice lab, along with the HTML file in module 4, can be accessed through the resource tab of the course. Please click on the below link, which will redirect you to the corresponding folder.

[https://www.coursera.org/learn/command-line-interface-and-scripting/resources/CnQ9z](https://www.coursera.org/learn/command-line-interface-and-scripting/resources/CnQ9z "Solutions Practice Labs - Week 4")




## **Reading Objective:**

In this reading, you will learn to create a file using vi editor. The reading will discuss basic vi editor operating modes and commands for deleting file content and copying and pasting text in vi editor. Finally, this reading will give an overview of some miscellaneous vi commands such as repeat action, search and replace, jump to line, indentation, marking text, split and join lines, and line number display.

## **Creating a File Using vi Editor**

## **vi Editor:**

vi is a widely used text editor in Unix and Unix-like operating systems. It's a command-line-based editor known for its powerful and efficient text manipulation capabilities. vi has different modes for navigation and editing, which can be confusing for beginners but offers great flexibility once mastered.

## **vi Editor Modes:**

**Normal Mode:** This is the default mode when you open a file in vi. In this mode, you can navigate the file, perform various operations, and issue commands.

**Insert Mode:** In this mode, you can directly insert and edit text. To enter Insert Mode from Normal Mode, press the "i" key.

**Command-Line Mode:** This mode is used for saving, quitting, searching, and other commands. To enter Command-Line Mode from Normal Mode, press ":" (colon).

## **vi Editor Options:**

\-r: Recover the file in case of a system crash or sudden termination.

\-c <command>: Run a command after opening the file.

\-n: Open the file in read-only mode.

\-i <backup\_extension>: Set a backup extension for files.

+<line\_number>: Open the file with the cursor at a specific line number.

## **Steps to Create a File Using vi Editor:**

**Open Terminal:** Open a terminal on your Unix-like system.

**Type vi <filename>:** Replace <filename> with the name of the file you want to create or edit.

vi my\_file.txt

**Enter Insert Mode:** By default, vi opens in Normal Mode. To start inserting text, press the "i" key.

**Type Text:** Start typing the content of your file.

**Save Changes:** Once you've entered your text, press the "Esc" key to exit Insert Mode and return to Normal Mode. Then, in Command-Line Mode, type:

:w

This command will save your changes.

**Quit vi Editor:** After saving your changes, you can quit vi by typing in Command-Line

:q

If you've made changes and want to quit without saving, use:

:q!

**Save and Quit:** If you want to save and quit simultaneously, use:

:wq

**Navigate and Edit:** While in Normal Mode, you can navigate using arrow keys or "h" (left), "j" (down), "k" (up), and "l" (right). You can delete characters with "x," delete lines with "dd," copy with "yy," paste with "p," and more.

## **Basic vi Editor Operating Modes**

## **Normal Mode:**

Launch the terminal and open vi by typing: vi filename (replace "filename" with the desired file name).

You'll start in Normal Mode. In this mode, you can navigate the file, delete text, copy text, and more, using single key commands.

Try navigating the cursor using "h" (left), "j" (down), "k" (up), and "l" (right) keys.

Delete a character: Press "x."

Delete a line: Press "dd."

Copy a line: Press "yy."

Paste the copied line: Press "p."

To enter Insert Mode, press "i."

## **Insert Mode:**

After pressing "i" in Normal Mode, you're in Insert Mode.

In Insert Mode, you can type and edit text as you would in a typical text editor.

Type some text, and then press the "Esc" key to return to Normal Mode.

## **Command Mode:**

After pressing "Esc" from Insert Mode or when initially opening vi, you're in Command Mode.

In Command Mode, you can issue various commands to save, quit, search, and more.

Save changes: Type :w and press Enter.

Quit vi: Type :q and press Enter.

Save and quit: Type :wq and press Enter.

Quit without saving changes: Type :q! and press Enter.

To enter Ex Command Mode, press ":" (colon).

## **Ex Command Mode:**

After pressing ":" in Command Mode, you enter Ex Command Mode.

Ex commands offer more advanced functionality, like searching and replacing text.

Search for a word: Type :/word and press Enter (replace "word" with the word you're searching for).

Replace text: Type :%s/old\_text/new\_text/g and press Enter (replace "old\_text" and "new\_text" as needed).

## **Practice Steps:**

Open your terminal and create a new text file using vi: vi my\_file.txt.

You're in Normal Mode by default. Try navigating around using "h," "j," "k," and "l."

Delete a character: Press "x." Undo with "u."

Delete a line: Press "dd." Undo with "u."

Copy a line: Press "yy."

Paste the copied line: Move to a new line, press "p."

Enter Insert Mode by pressing "i." Type some text.

Press "Esc" to return to Normal Mode.

Save the changes: In Command Mode, type :w and press Enter.

Quit vi: In Command Mode, type :q and press Enter.

Reopen the file: vi my\_file.txt.

Search for a word: In Ex Command Mode, type :/search\_word and press Enter.

Replace text: In Ex Command Mode, type :%s/old\_text/new\_text/g and press Enter.

Remember, practicing these steps will help you become more comfortable with the different modes and commands in the vi editor. Over time, you'll become proficient at using vi for text editing tasks.

## **Commands for Deleting File Content**

## **Delete a Character:**

Position the cursor over the character you want to delete.

Press the "x" key to delete the character under the cursor.

## **Delete a Line:**

Position the cursor on the line you want to delete.

Press the "dd" keys to delete the entire line.

## **Delete Multiple Lines:**

Position the cursor on the first line you want to delete.

Press the number of lines you want to delete followed by the "dd" keys. For example, to delete 3 lines, press "3dd."

## **Delete from Cursor to End of Line:**

Position the cursor where you want to start deleting.

Press the "D" (capital "D") key to delete from the cursor to the end of the line.

## **Delete Word:**

Position the cursor at the beginning of the word you want to delete.

Press the "dw" keys to delete the word under the cursor.

## **Delete Word and Remain in Normal Mode:**

Position the cursor at the beginning of the word you want to delete.

Press "daw" (delete around word) to delete the word under the cursor along with surrounding spaces.

## **Common Shortcut Keys in vi Editor:**

**Switch to Insert Mode:**

Press "i" to enter Insert Mode before the cursor.

Press "I" (capital "I") to enter Insert Mode at the beginning of the line.

Press "a" to enter Insert Mode after the cursor.

Press "A" (capital "A") to enter Insert Mode at the end of the line.

**Save and Quit:**

Press ":wq" and Enter to save changes and quit the vi editor.

**Quit Without Saving:**

Press ":q!" and Enter to quit the vi editor without saving changes.

**Undo:**

Press "u" to undo the last change.

**Redo:**

Press "Ctrl" + "r" to redo an undone change.

**Navigate to Beginning/End of Line:**

Press "0" (zero) to move to the beginning of the line.

Press "$" to move to the end of the line.

**Navigate to Beginning/End of File:**

Press "gg" to move to the beginning of the file.

Press "G" (capital "G") to move to the end of the file.

**Search:**

Press "/" to enter search mode, then type the search term and press Enter.

Press "n" to move to the next occurrence of the search term.

**Replace:**

Position the cursor on the character you want to replace.

Press "r" followed by the new character.

Remember that these are just a few of the many commands and shortcuts available in the vi editor. Practice and exploration will help you become more proficient and comfortable with using vi for text editing tasks.

## **Copying and Pasting Text in vi Editor**

## **Normal Mode:**

When you open a file in vi, you start in Normal Mode.

In this mode, you can navigate through the text and issue commands.

## **Copy a Line:**

Position the cursor on the line you want to copy.

Press the "yy" keys. This command yanks (copies) the entire line into a buffer.

## **Paste Copied Line:**

Position the cursor on the line where you want to paste the copied line.

Press the "p" key. This command puts (pastes) the copied line below the cursor.

## **Cut a Line:**

Position the cursor on the line you want to cut.

Press the "dd" keys. This command deletes the line and places it in a buffer.

## **Paste Cut Line:**

Position the cursor on the line where you want to paste the cut line.

Press the "p" key. This command puts (pastes) the cut line below the cursor.

## **Copy Multiple Lines:**

Position the cursor on the first line you want to copy.

Press the number of lines you want to copy, followed by "yy." For example, to copy 3 lines, press "3yy."

## **Paste Copied Lines:**

Position the cursor where you want to paste the copied lines.

Press the "p" key. This command puts (pastes) the copied lines below the cursor.

## **Copy to End of Line:**

Position the cursor anywhere on the line you want to copy.

Press "y$" to yank (copy) from the cursor to the end of the line.

## **Copy Text Within a Range of Lines:**

In Normal Mode, type :<start\_line>,<end\_line>y and press Enter. Replace <start\_line> and <end\_line> with line numbers.

For example, to copy lines 5–8, type :5,8y and press Enter.

## **Copy Text Using Visual Mode:**

Press "v" to enter Visual Mode. This mode allows you to select text using movement keys.

Navigate to select the desired text.

Press "y" to yank (copy) the selected text.

**Example:**

Open a file in vi: vi my\_file.txt.

Position cursor on a line, press "yy" to copy it.

Move to another line, press "p" to paste the copied line.

To copy multiple lines, press "3yy" to copy 3 lines.

Move to another location, press "p" to paste the copied lines.

By mastering these commands, you can efficiently copy and paste text within the vi editor to streamline your editing tasks.

## **Miscellaneous vi Commands**

## **Repeat Action:**

To repeat the last change made, press "." (period).

## **Search and Replace:**

Search for a word: Press "/" to enter search mode, type the word, press Enter.

Replace word: Position cursor on word, type ":s/old/new/g" and press Enter.

Replace all occurrences: Use ":s/old/new/gc" to replace with confirmation.

## **Jump to Line:**

Go to a specific line: In Normal Mode, type ":<line\_number>" and press Enter.

## **Indentation:**

Indent a line: Position cursor on line, press ">>"

Unindent a line: Position cursor on line, press "<<"

## **Marking Text:**

Set a mark: In Normal Mode, press "m" followed by a letter (e.g., "ma").

Jump to mark: In Normal Mode, press "\`" (backtick) followed by the mark letter (e.g., "a").

## **Split and Join Lines:**

Split line at cursor: Press "s" in Normal Mode.

Join lines: Position cursor on the first line, type ":join" and press Enter.

## **Line Number Display:**

Toggle line numbers display: In Normal Mode, type ":set number" or ":set nonumber" and press Enter.

**Examples:**

**Search and Replace:**

Search for "apple": Press "/" and type "apple," Enter.

Replace "apple" with "orange": Type ":s/apple/orange/g" and Enter.

**Jump to Line:**

Go to line 25: In Normal Mode, type ":25" and Enter.

**Indentation:**

Indent a line: Position cursor on line, press ">>..

Unindent a line: Position cursor on line, press "<<."

**Marking Text:**

Set mark "a": In Normal Mode, press "ma."

Jump to mark "a": In Normal Mode, press "\`a."

**Split and Join Lines:**

Split line at cursor: Press "s" in Normal Mode.

Join lines: Position cursor on the first line, type ":join" and press Enter.

**Toggle Line Numbers Display:**

Display line numbers: In Normal Mode, type ":set number" and Enter.

Hide line numbers: In Normal Mode, type ":set nonumber" and Enter.

Remember that mastering these miscellaneous commands will enhance your productivity and efficiency when working with the vi editor. Regular practice is key to becoming proficient.

## **Searching in vi Editor**

## **Basic Searching:**

In Normal Mode, press "/" to enter search mode.

Type the word or pattern you want to search for, and press Enter.

To find the next occurrence, press "n." To find the previous occurrence, press "N."

## **Pattern Searching in vi Editor:**

**Regular Expression Patterns:**

vi supports regular expressions for advanced pattern matching.

Common patterns: . (any character), \* (zero or more occurrences), ^ (start of line), $ (end of line).

**Case-Insensitive Search:**

Use the "\\c" or "\\C" modifier before the search pattern to make the search case-insensitive or sensitive, respectively.

**Example:** /\\csearch or /\\CSearch.

## **Substitution of Text in vi Editor:**

**Substitute Command:**

In Normal Mode, press ":" to enter Command-Line Mode.

To replace the first occurrence of a word with another word, use :s/old\_word/new\_word/.

To replace all occurrences on the current line, add "g" flag :s/old\_word/new\_word/g.

To replace all occurrences in the entire file, use :%s/old\_word/new\_word/g.

To confirm each replacement interactively, use :%s/old\_word/new\_word/gc.

**Substitute with Patterns:**

Regular expressions can be used in the substitute command.

Example: :%s/\\d+/NUMBER/g replaces all occurrences of digits with "NUMBER."

**Examples:**

**Basic Searching:**

Open a file in vi: vi my\_file.txt.

Press "/" and type "search\_term," Enter.

Press "n" to find the next occurrence.

**Pattern Searching:**

Open a file in vi: vi my\_file.txt.

Press "/" and type ^start, Enter to find lines starting with "start."

Press "/" and type end$, Enter to find lines ending with "end."

**Case-Insensitive Search:**

Open a file in vi: vi my\_file.txt.

Press "/" and type /\\csearch, Enter to find "search" regardless of case.

**Substitution of Text:**

Open a file in vi: vi my\_file.txt.

Press ":" to enter Command-Line Mode.

Type :%s/old\_text/new\_text/g, Enter to replace all occurrences of "old\_text" with "new\_text."

**Substitute with Patterns:**

Open a file in vi: vi my\_file.txt.

Press ":" to enter Command-Line Mode.

Type :%s/\\d+/NUMBER/g, Enter to replace all digits with "NUMBER."

**Important Tips:**

Be cautious when using substitutions, especially with the "g" (global) flag, to avoid unintended replacements.

Regular expressions can be powerful but require practice to use effectively.

By understanding and practicing these techniques, you can efficiently search for patterns and perform text substitutions in the vi editor to enhance your text editing workflow.

## **Reading Summary**

In this reading, you have learned the following:

-   Creating a file using vi editor
    
-   Basic vi editor operating modes
    
-   Commands for deleting file content
    
-   Copying and pasting text in vi editor
    
-   Miscellaneous vi commands



The solutions for the practice lab, along with the HTML file in module 5, can be accessed through the resource tab of the course. Please click on the below link, which will redirect you to the corresponding folder.

[https://www.coursera.org/learn/command-line-interface-and-scripting/resources/3ySxz](https://www.coursera.org/learn/command-line-interface-and-scripting/resources/3ySxz "Solutions Practice Labs - Week 5")





## **Reading Objective:**

In this reading, you will learn about auto recovery, backup, and version control in Vi editor. The reading will discuss version control and recovery after a crash in the Vi editor and pasting text in Vi editor. You will also learn how to undelete and recover from a buffer. Finally, this reading will give an overview of mark command.

## **Auto Recovery, Backup, and Version Control in Vi Editor**

Vi is a powerful and widely used text editor in Unix-like operating systems. It offers several features to enhance your editing experience, including auto recovery, backup, and version control. This handout provides an overview of these features and how to utilize them effectively.

## **Auto Recovery:**

Auto recovery ensures that your work is saved periodically, minimizing the risk of losing data due to unexpected crashes or system failures. In Vi, this feature is managed through the “viminfo” file.

To enable auto recovery, add the following line to your ~/.vimrc file:

set viminfo='1000,<s1000

## **Backup:**

Vi allows you to create backup files for the documents you edit. Backup files are copies of your original files, which can be useful if you need to revert to a previous version.

To enable backup file creation, add the following line to your ~/.vimrc file:

set backup

By default, backup files are created with a ~ suffix. You can customize this behavior using the backupext option. For example:

set backupext=.bak

## **Version Control:**

While Vi doesn't have built-in version control like Git, you can use external version control systems alongside Vi for tracking changes and collaborating with others.

Initialize a Git repository in your project directory using:

git init

Regularly commit your changes using Git commands like:

git add <filename>

git commit -m "Commit message"

You can integrate Git with Vi using plugins like Fugitive:

Plugin “tpope/vim-fugitive”

Fugitive offers commands like :Gstatus, :Gadd, and :Gcommit to interact with Git without leaving Vi.

## **Tips for Efficient Editing:**

Frequent Saving: Make it a habit to save your work frequently using the :w command. This prevents data loss in case of unexpected events.

Buffers and Tabs: Utilize buffers (:bnext, :bprev) and tabs (:tabnew, :tabnext) to manage multiple files efficiently.

Undo/Redo: Vi provides undo and redo functionalities using u and Ctrl + r, respectively.

Navigation: Master Vi's navigation commands (h, j, k, l, w, b, gg, G) to move swiftly within your text.

Search and Replace: Use / to search and :s to replace text. Add flags like g for global replacement.

Auto recovery, backup, and version control are essential features for maintaining your work and collaborating effectively. By understanding and utilizing these features in the Vi editor, you can enhance your productivity and minimize the risks associated with data loss.

## **Notes on Version Control in Vi Editor**

Version control is a crucial aspect of software development that allows you to track changes made to your files over time, collaborate with others, and easily revert to previous versions. While Vi itself doesn't provide built-in version control, you can seamlessly integrate popular version control systems like Git with Vi to manage your projects effectively.

## **1\. Using Git with Vi:**

Git is a distributed version control system that helps you track changes to your files and collaborate with others. You can use Git alongside Vi to manage your project's version history.

## **2\. Setting Up Git:**

Initialize a Git Repository: Navigate to your project directory in the terminal and run:

git init

Adding and Committing Changes:

a. Add Changes: After editing a file in Vi, save your changes with :w and then stage the changes using Git:

git add <filename>

b. Commit Changes: Commit your staged changes along with a descriptive message:

git commit -m "Add a descriptive commit message here"

## **3\. Common Git Commands:**

git status: Check the status of your repository, showing modified and staged files.

git log: View the commit history, including commit messages, authors, and timestamps.

git diff: Display differences between your working directory and the last commit.

git checkout: Switch between branches or restore files from a specific commit.

git branch: List, create, or delete branches.

git merge: Combine changes from different branches.

## **4\. Integrating Git with Vi using Fugitive Plugin:**

The Fugitive plugin provides seamless Git integration within Vi, enhancing your version control workflow.

Install Fugitive Plugin: If you're using a plugin manager like Vundle or Vim-Plug, add the following line to your ~/.vimrc:

Plugin “tpope/vim-fugitive”

Using Fugitive Commands:

a. :Gstatus: Open a split window to view and stage changes.

b. :Gcommit: Open a split window to create a commit with a message.

c. :Gblame: Annotate each line in the file with the author and commit information.

d. :Gdiff: See the differences between the working directory and the last commit.

e. :Glog: Display a log of commits in the current repository.

## **5\. Example:**

Let's say you're working on a Python script named app.py and want to version control it using Git and Vi.

Initialize Git repository:

git init

Edit app.py in Vi, save changes (:w), stage changes (git add app.py), and commit changes (git commit -m "Initial commit").

Make additional changes in Vi, stage, and commit them.

Use Fugitive to view commit history:

Open app.py in Vi.

Enter :Glog to view the commit history.

Integrating Git with Vi using tools like Fugitive allows you to manage version control efficiently, track changes, collaborate with others, and maintain a well-organized project history. By mastering these techniques, you can enhance your development workflow and ensure the integrity of your codebase over time.

## **Recovery After Crash in Vi Editor**

Vi is a powerful text editor commonly used in Unix-like operating systems. While working on your files in Vi, unexpected crashes or system failures can occur, potentially leading to data loss. However, Vi provides mechanisms for recovering your work and minimizing the impact of such incidents. This article discusses how to recover your files and regain your work after a crash in Vi, along with suitable examples.

## **1\. Recovery Options in Vi:**

Vi offers several features to help you recover your work after a crash:

a. Swap Files: Vi creates swap files (files with .swp extension) as a form of temporary backup while you edit. In case of a crash, these swap files can be used to recover unsaved changes.

b. Undo History: Vi maintains an undo history, allowing you to revert recent changes. This history can be particularly useful after a crash.

c. Auto Recovery: Vi can be configured to automatically recover your unsaved changes when you reopen a file after a crash.

## **2\. Recovering from a Crash - Example:**

Let's consider an example where you were editing a file named document.txt in Vi and a crash occurred before you could save your changes.

**Swap File Recovery:**

If a crash happens while you're editing document.txt, a swap file named .document.txt.swp is created in the same directory.

After the crash, open a terminal and navigate to the directory containing document.txt.

Use the following command to recover the swap file:

vim -r .document.txt.swp

Vi will open the swap file, and you can recover your unsaved changes.

**Undo History Recovery:**

Open document.txt again in Vi after the crash.

Use the u command to undo changes or press Ctrl + r to redo changes.

Navigate through the undo history to restore your file to the desired state.

Auto Recovery:

Vi can be configured to save recovery information to the ~/.viminfo file, which helps recover unsaved changes after a crash.

To enable auto recovery, add the following line to your ~/.vimrc:

set viminfo='1000,<s1000

After a crash, open document.txt again in Vi. Vi will prompt you to recover the file using the auto-recovery information.

## **3\. Preventing Data Loss:**

To minimize the risk of data loss due to crashes:

Frequent Saving: Develop a habit of saving your work frequently using :w to update your changes.

Backup Files: Enable backup file creation using set backup in your ~/.vimrc to create a backup copy of your files.

## **4\. Conclusion:**

Recovering your work after a crash in Vi is possible through swap file recovery, undo history, and auto-recovery mechanisms. By understanding these recovery options and implementing preventative measures, you can ensure that your progress is preserved even in the face of unexpected crashes or system failures.

## **Undelete and Recover from Buffer**

Vi is a powerful text editor with a wide range of features to enhance your editing experience. Among these features are the ability to undelete text and recover content from the buffer, providing you with greater control and flexibility while editing. This handout provides an overview of how to use the undelete and buffer recovery functions in Vi.

## **1\. Undelete in Vi:**

Accidentally deleting text can be frustrating, but Vi offers a straightforward way to recover it.

**Undelete the Last Deleted Text:**

Use the u command to undo the last change, including deletions. Press u immediately after deleting text to restore it.

**Recover Deleted Text with Registers:**

Vi stores deleted text in numbered and named registers. To recover deleted text from a specific register, use “xP,” where x is the register number or name. For example, "0P" retrieves text from the "0" register.

## **2\. Recover from Buffer in Vi:**

The buffer in Vi is a temporary storage area where text is stored before being pasted or deleted. You can use the buffer to recover or paste text.

**Recover Last Deleted Text:**

The p command pastes the contents of the buffer after the cursor. After deleting text, you can recover it by simply pressing p.

**Recover Specific Text from Buffer:**

You can access the buffer contents using registers. For example, "1p" pastes the most recently deleted text, and "2p" pastes the text before that.

Practical Examples:

Let's explore some practical examples of using the undelete and buffer recovery functions in Vi.

**Undelete:**

Type some text: This is an example sentence.

Accidentally delete a portion: This is an example.

Press u to undo the deletion and recover the deleted text.

**Recover from Buffer:**

Type some text: Hello, World!

Delete the text: Hello,.

Type more text: How are you?

Accidentally deleted text: Hello,.

Press "1p" to paste the deleted text.

**Additional Tips:**

Multiple Undos: Press u multiple times to undo multiple changes.

Registers: Vi stores deleted text in numbered registers (0–9) and named registers (a–z). Deleted text is added to the "0" register by default.

Named Registers: Use "xy" to yank (copy) text to register x, and "xp" to paste it.

Recover More: You can recover more extensive portions of deleted or overwritten text by utilizing the named registers.

Undelete and buffer recovery features in Vi provide a safety net for your editing process. Whether you've accidentally deleted text or need to retrieve previously deleted content, understanding these functions will help you work more confidently and efficiently in Vi, ensuring that your work remains intact and organized.

## **mark command**

In the Vi text editor, the mark command allows you to set marks (bookmarks) at specific locations within a file. These marks are essentially pointers that help you quickly navigate to those locations later. The mark command is a powerful feature that enhances your ability to move efficiently within your document. This explanation will provide detailed insights into how the mark command works, along with suitable examples.

## **1\. Setting Marks:**

To set a mark in Vi, follow these steps:

Place the cursor at the desired location within your file.

Press m followed by a lowercase letter (a–z) to set the mark.

For example, to set a mark at the current cursor position using the letter "a," you would press ma.

## **2\. Navigating to Marks:**

After you've set marks, you can use them to quickly navigate within your file.

To move the cursor to a mark, press ' (apostrophe) followed by the mark letter.

For example, to move the cursor to the mark set with "a," you would press 'a.

To jump to the beginning of the line where the mark is set, use \` (backtick) followed by the mark letter.

For example, to jump to the beginning of the line containing the mark "a," you would press \`a.

## **3\. Deleting Marks:**

To delete a mark, use the :delmarks command followed by the mark letter.

For example, to delete the mark set with "a," you would type :delmarks a.

**Examples:**

Let's explore some practical examples of using the mark command in Vi:

**Setting Marks:**

Open a file in Vi.

Move the cursor to a specific line, e.g., line 10.

Set a mark at the current cursor position using ma.

**Navigating to Marks:**

After setting the mark, move the cursor elsewhere in the file.

Return to the marked location by pressing 'a.

**Jumping to Beginning of Line:**

After setting the mark, move the cursor elsewhere in the file.

Jump to the beginning of the line containing the mark by pressing \`a.

**Deleting Marks:**

Set multiple marks at different locations.

Use :delmarks followed by the mark letters you want to delete, e.g., :delmarks ab.

You can use any lowercase letter (a–z) as a mark. Each letter can be associated with a unique location.

Marks are specific to the open file. They won't be available when you close and reopen the file.

The mark command in Vi provides a convenient way to bookmark specific locations within your text file. By setting and navigating to marks, you can easily jump between different parts of your document, enhancing your editing efficiency. Understanding and incorporating the mark command into your Vi workflow can greatly streamline your text editing tasks.

## **Reading Summary**

In this reading, you have learned the following:

-   Auto recovery, backup, and version control in the Vi editor
    
-   Notes on version control in the Vi editor
    
-   Recovery after crash in Vi editor
    
-   Undelete and recover from buffer
    
-   mark command



## **Reading Objective:**

In this reading, you will learn about Linux standard input redirection and Linux standard output redirection and appending output. The reading will focus on Linux standard error redirection and the usage of /dev/null in Linux.

## **Linux Standard Input Redirection**

Standard input (stdin) is a fundamental concept in Linux that allows you to provide input to a command or program.

Input redirection is a technique used to change the source of input for a command or program, allowing you to provide input from a file or another command instead of directly from the keyboard. This can be incredibly useful for automating tasks, processing large amounts of data, and combining multiple commands.

**Syntax:**

command < input\_file

**Examples:**

**Using a File as Input:**

Let us say you have a file named input.txt containing the following text:

Hello, Linux!

This is an example of input redirection.

**Command:**

cat < input.txt

**Output:**

Hello, Linux!

This is an example of input redirection.

**Counting Words in a File:**

You can use the wc command to count the number of words, lines, and characters in a file.

**Command:**

wc -w < input.txt

**Output:**

11

**Using Input Redirection with Pipes:**

You can combine input redirection with pipes to create powerful data processing pipelines.

**Command:**

cat input.txt | grep "example" | wc -l

**Output:**

1

**Running a Script with Input Redirection:**

Consider you have a Python script named myscript.py that reads two numbers and calculates their sum.

**Script (myscript.py):**

num1 = float(input("Enter the first number: "))

num2 = float(input("Enter the second number: "))

print("Sum:", num1 + num2)

**Command:**

python myscript.py < input.txt

**Output (if input.txt contains 5.5 and 7.3):**

Enter the first number: Enter the second number: Sum: 12.8

**Using the sort Command:**

The sort command can be used to sort lines of text in a file.

**Command:**

sort < unsorted.txt

**Output (if unsorted.txt contains unsorted lines):**

apple

banana

grape

orange

**Note**: Input redirection uses the < symbol to indicate that the command should take its input from the specified file instead of the keyboard. Keep in mind that the standard input redirection only affects commands that read input from stdin. It does not work for all commands, especially those that do not read input or expect input from other sources.

## **Linux Standard Output Redirection and Appending Output**

In Linux, standard output (stdout) is the default stream where commands and programs send their output. By default, the stdout is directed to the terminal or command prompt, allowing you to see the results of your commands. However, you can use output redirection to change the destination of this output, either by replacing or appending to existing files. This is especially useful for capturing and storing command output or for creating log files.

**Syntax:**

**Standard Output Redirection (Replace):**

command > output\_file

**Standard Output Appending:**

command >> output\_file

**Examples:**

**Redirecting Output to a File:**

**Command:**

ls /usr/bin > file\_list.txt

**Result:** The output of the ls command, which lists the files in the /usr/bin directory, will be stored in the file\_list.txt file, replacing any existing content.

**Appending Output to a File:**

**Command:**

echo "New line of text" >> file\_list.txt

**Result:** The text "New line of text" will be appended to the end of the file\_list.txt file without affecting the existing content.

**Redirecting Error Messages:**

You can also redirect error messages (stderr) to a file using 2>.

**Command:**

ls /nonexistent\_directory 2> error.log

**Result:** The error message generated by the failed ls command will be saved in the error.log file.

**Redirecting Both Output and Error:**

You can redirect both standard output and error messages to separate files.

**Command:**

ls /usr/bin > file\_list.txt 2> error.log

**Result:** The list of files from /usr/bin will be redirected to file\_list.txt, and any error message will be saved in error.log.

**Redirecting and Appending Simultaneously:**

**Command:**

date > timestamp.log

date >> timestamp.log

**Result:** The current date and time will be written to timestamp.log, and a subsequent date command will append a new timestamp to the end of the file.

**Redirecting Command Output to Another Command:**

**Command:**

ls /usr/bin | grep "zip" > zip\_files.txt

**Result:** The list of files from /usr/bin containing the word "zip" will be saved in the zip\_files.txt file.

**Creating a Log File:**

**Command:**

./my\_script.sh > log.txt 2>&1

**Result:** The output (stdout) and any error messages (stderr) from my\_script.sh will be redirected to log.txt.

**Note:**

The > operator overwrites the file with new content, whereas >> appends content to the file.

The 2> operator redirects stderr.

2>&1 combines stderr with stdout, sending both to the same destination.

Standard output redirection and appending are essential techniques for managing command output, creating logs, and automating data collection tasks in a Linux environment. They provide flexibility in handling output streams and capturing information for later analysis.

## **Linux Standard Error Redirection**

In Linux, standard error (stderr) is the default stream where error messages and diagnostic information from commands and programs are displayed. By default, stderr is directed to the terminal or command prompt, allowing you to see error messages as they occur. However, you can use stderr redirection to capture and manage error messages separately from standard output (stdout). This can be helpful for debugging, logging, and error analysis.

**Syntax:**

command 2> error\_file

**Examples:**

Redirecting Standard Error to a File:

**Command:**

ls /nonexistent\_directory 2> error.log

**Result:** The error message generated by the failed ls command will be saved in the error.log file, leaving standard output (stdout) unaffected.

**Redirecting Standard Error and Standard Output:**

You can redirect both stderr and stdout to separate files.

**Command:**

ls /usr/bin > file\_list.txt 2> error.log

**Result:** The list of files from /usr/bin will be redirected to file\_list.txt, and any error message will be saved in error.log.

**Redirecting Standard Error to Standard Output:**

You can merge stderr with stdout using the 2>&1 syntax.

**Command:**

ls /nonexistent\_directory > output.log 2>&1

**Result:** Both the output and the error message from the failed ls command will be combined and redirected to the output.log file.

**Appending Standard Error to a File:**

**Command:**

echo "Error: Something went wrong!" >> error.log 2>&1

**Result:** The error message will be appended to the error.log file, along with any existing content.

**Redirecting Standard Error to Null:**

**Command:**

ls /usr/bin/nonexistent\_file 2> /dev/null

**Result:** The error message generated by the failed ls command will be discarded, and no output will be shown.

**Redirecting and Appending Standard Error:**

**Command:**

./my\_script.sh >> output.log 2>> error.log

**Result:** The output (stdout) from my\_script.sh will be appended to output.log, and any error messages (stderr) will be appended to error.log.

**Redirecting and Displaying Standard Error:**

**Command:**

ls /usr/bin /nonexistent\_directory 2>&1 | grep "bin"

**Result:** The combined output of the ls command and the error message will be piped to grep, which will search for lines containing "bin."

**Note:**

Standard error redirection allows you to manage error messages independently from standard output, enabling effective error tracking, debugging, and log file creation in Linux. It helps you keep a record of errors, diagnose issues, and improve the reliability of your scripts and commands.

## **Using /dev/null in Linux**

In Linux, /dev/null is a special device file that provides a way to discard data written to it and produces no output when read from. It is often used as a sink for unwanted output, a way to suppress output, or to discard data without storing it. /dev/null is particularly useful when you want to silence or ignore certain outputs, especially in scripts and command line operations.

**Redirecting Output to /dev/null:**

/dev/null can be used to discard standard output (stdout) or standard error (stderr) streams.

**Syntax:**

**Redirecting Standard Output to /dev/null:**

command > /dev/null

**Redirecting Standard Error to /dev/null:**

command 2> /dev/null

**Redirecting Both Standard Output and Standard Error to /dev/null:**

command > /dev/null 2>&1

**Examples:**

**Silencing Output:**

**Command:**

echo "This message will disappear" > /dev/null

**Result:** The output of the echo command is discarded and not displayed.

**Suppressing Error Messages:**

**Command:**

ls /nonexistent\_directory 2> /dev/null

**Result:** The error message generated by the failed ls command is discarded.

**Silencing Both Output Streams:**

**Command:**

rm nonexistent\_file > /dev/null 2>&1

**Result:** Both standard output and standard error from the rm command are discarded.

**Redirecting Output, Discarding Error:**

**Command:**

ls /usr/bin /nonexistent\_directory 2> /dev/null

**Result:** The output of the ls command is displayed, and the error message is discarded.

**Running a Command Quietly:**

**Command:**

make > /dev/null

**Result:** The output of the make command is suppressed.

**Redirecting and Discarding Output:**

**Command:**

./my\_script.sh > /dev/null 2>&1

**Result:** Both the standard output and standard error from my\_script.sh are discarded.

**Benefits and Use Cases:**

-   Efficiently suppress unwanted output in scripts and automated tasks.
    
-   Minimize clutter in terminal windows when executing commands.
    
-   Create "quiet" or "silent" execution modes for scripts.
    
-   Redirect output when testing commands or running background tasks.
    

**Note:**

/dev/null does not store data; it effectively discards it.

When redirecting output to /dev/null, no files are created or modified.

Using /dev/null is a powerful technique for controlling output, silencing errors, and enhancing the efficiency and usability of your Linux command line operations and scripts.

## **Reading Summary**

In this reading, you have learned the following:

-   Linux Standard Input Redirection
    
-   Linux Standard Output Redirection and Appending Output
    
-   Linux Standard Error Redirection
    
-   Usage of /dev/null in Linux





## **Reading Objective:**

In this reading, you will learn about the Linux sort command used to rearrange lines of text in either ascending or descending order. The reading also gives an overview of other Linux commands, such as head, tail, grep, pipe, and tee.

## **Linux sort Command**

The sort filter in Linux is used to rearrange lines of text in either ascending or descending order. It is often combined with other commands to filter and process data in various ways, allowing you to extract specific information, remove duplicates, and create custom reports. The sort filter is a versatile tool that enhances data manipulation and analysis in the Linux command line environment.

**Syntax:**

sort \[options\] \[file\]

**Common Options:**

\-r: reverses the sorting order (descending).

\-n: sorts numerically.

\-k: specifies a key or field for sorting.

\-u: removes duplicate lines.

\-f: performs case-insensitive sorting.

\-o: outputs sorted result to a file.

**Examples:**

**Basic Text Sorting:**

**Command:**

sort file.txt

**Input (file.txt):**

banana

apple

grape

orange

**Output:**

apple

banana

grape

orange

**Numeric Sorting:**

**Command:**

sort -n numbers.txt

**Input (numbers.txt):**

10

2

100

50

**Output:**

2

10

50

100

**Reverse Sorting:**

**Command:**

sort -r file.txt

**Input (file.txt):**

apple

banana

grape

orange

**Output:**

orange

grape

banana

apple

**Sort Using Specific Fields:**

**Command:**

sort -k 2,2 data.txt

**Input (data.txt):**

Alice 25

Bob 22

Carol 30

**Output:**

Bob 22

Alice 25

Carol 30

**Case-Insensitive Sorting:**

**Command:**

sort -f names.txt

**Input (names.txt):**

Alice

bob

Carol

david

**Output:**

Alice

bob

Carol

david

**Removing Duplicate Lines:**

**Command:**

sort -u duplicates.txt

**Input (duplicates.txt):**

apple

banana

apple

grape

**Output:**

apple

banana

grape

**Sorting and Saving to a File:**

**Command:**

sort input.txt -o sorted\_output.txt

**Input (input.txt):**

banana

apple

grape

orange

**Output (sorted\_output.txt):**

apple

banana

grape

orange

**Benefits and Use Cases:**

-   Organize data for better readability and analysis.
    
-   Prepare data for further processing or reporting.
    
-   Remove duplicates from datasets.
    
-   Generate sorted output for scripts and pipelines.
    

The sort command is a versatile tool for sorting and arranging text lines in various orders. Whether you are working with simple lists, numerical data, or more complex datasets, the sort command provides essential functionality for data manipulation in the Linux command line environment.

## **Linux head Command: Viewing the Beginning of Files**

The head command in Linux is used to display the first few lines of a file or input from a stream. It is commonly used to preview the beginning of text files, log files, and other types of files without having to display the entire contents. The head command is especially useful for quickly assessing the structure or content of a file.

**Syntax:**

head \[options\] \[file\]

**Common Options:**

\-n N: displays the first N lines (default is 10).

\-c N: displays the first N bytes instead of lines.

**Examples:**

**Displaying the First Ten Lines of a File:**

**Command:**

head file.txt

**Input (file.txt):**

Line 1

Line 2

Line 3

...

Line 10

Line 11

Line 12

**Output:**

Line 1

Line 2

Line 3

...

Line 10

**Displaying a Specific Number of Lines:**

**Command:**

head -n 5 file.txt

**Input (file.txt):**

Line 1

Line 2

Line 3

Line 4

Line 5

**Output:**

Line 1

Line 2

Line 3

Line 4

Line 5

**Displaying Bytes Instead of Lines:**

**Command:**

head -c 20 file.txt

**Input (file.txt):**

This is a sample text file.

**Output:**

This is a sample te

**Combining head with Other Commands:**

**Command:**

cat data.txt | head -n 3

**Input (data.txt):**

Apple

Banana

Orange

Grape

**Output:**

Apple

Banana

Orange 

**Using Wildcards to Preview Multiple Files:**

**Command:**

head \*.log

**Input (file1.log):**

Log data for File 1

**Input (file2.log):**

Log data for File 2

**Output:**

\==> file1.log <==

Log data for File 1

\==> file2.log <==

Log data for File 2

**Benefits and Use Cases:**

-   Quickly preview the beginning of large files without loading the entire content.
    
-   Assess the structure or format of a file before further processing.
    
-   Review log files to check recent activities.
    
-   Combine with other commands to analyze or manipulate specific sections of files.
    

The head command is a handy utility for quickly inspecting the beginning of files, making it an essential tool for efficient file analysis and exploration in the Linux command line environment.

## **Linux tail Command: Viewing the End of Files**

The tail command in Linux is used to display the last few lines of a file or input from a stream. It is particularly useful for monitoring log files, checking the latest entries, and observing real-time changes in text files. The tail command allows you to quickly view the most recent content without reading through the entire file.

**Syntax:**

tail \[options\] \[file\]

**Common Options:**

\-n N: displays the last N lines (default is 10).

\-c N: displays the last N bytes instead of lines.

\-f: follows the file and displays new content as it is added (similar to tail -n 0 -f).

**Examples:**

Displaying the Last Ten Lines of a File:

**Command:**

tail file.txt

**Input (file.txt):**

Line 1

Line 2

Line 3

...

Line 10

Line 11

Line 12

**Output:**

Line 3

...

Line 10

Line 11

Line 12

**Displaying a Specific Number of Lines:**

**Command:**

tail -n 5 file.txt

**Input (file.txt):**

Line 1

Line 2

Line 3

Line 4

Line 5

**Output:**

Line 1

Line 2

Line 3

Line 4

Line 5

**Displaying Bytes Instead of Lines:**

**Command:**

tail -c 20 file.txt

**Input (file.txt):**

This is a sample text file.

**Output:**

sample text file.

**Following a File in Real-Time (Using -f):**

**Command:**

tail -f log.txt

**Output (real-time updates as the file changes):**

Log entry 1

Log entry 2

Log entry 3

...

**Combining tail with Other Commands:**

**Command:**

grep "Error" server.log | tail -n 10

**Input (server.log):**

Info: Server started.

Warning: Disk space low.

Error: Connection lost.

**Output:**

Error: Connection lost.

**Benefits and Use Cases:**

-   Monitor log files for recent activities and errors.
    
-   Observe real-time changes in files, such as log updates.
    
-   Quickly review the end of large files without reading from the beginning.
    
-   Combine with other commands for focused analysis and troubleshooting.
    

The tail command is a versatile tool for viewing the end of files, making it essential for log analysis, tracking updates, and gaining insight into recent events in the Linux command line environment.

## **Linux grep Command: Searching for Text Patterns**

The grep command in Linux is a powerful tool used for searching and filtering text within files or input streams. It allows you to locate lines that match a specified pattern, making it indispensable for text processing, log analysis, and data extraction tasks. The grep command supports regular expressions and offers various options for versatile and efficient text searching.

**Syntax:**

grep \[options\] pattern \[file...\]

**Common Options:**

\-i: performs a case-insensitive search.

\-r or -R: recursively searches directories.

\-l: lists filenames containing the pattern.

\-v: inverts the search, showing lines that do not match.

\-c: displays only the count of matching lines.

\-n: displays line numbers along with matching lines.

**Examples:**

**Basic Text Search:**

**Command:**

grep "error" logfile.txt

**Input (logfile.txt):**

Line 1: Info: Server started.

Line 2: Error: Connection lost.

Line 3: Warning: Disk space low.

**Output:**

Line 2: Error: Connection lost.

**Case-Insensitive Search:**

**Command:**

grep -i "WARNING" logfile.txt

**Input (logfile.txt):**

Line 1: Info: Server started.

Line 2: Error: Connection lost.

Line 3: WARNING: Disk space low.

**Output:**

Line 3: WARNING: Disk space low.

**Recursive Directory Search:**

**Command:**

grep -r "keyword" /path/to/search/

**Output:**

/path/to/search/file1.txt: keyword found

/path/to/search/subdir/file2.txt: keyword found

**Counting Matching Lines:**

**Command:**

grep -c "pattern" data.txt

**Input (data.txt):**

Line 1: This is a pattern.

Line 2: Another pattern here.

Line 3: No pattern in this line.

**Output:**

2

**Inverting the Search:**

**Command:**

grep -v "success" log.txt

**Input (log.txt):**

Operation failed

Task completed successfully

Unable to proceed

**Output:**

Operation failed

Unable to proceed

**Benefits and Use Cases:**

-   Search for specific information in log files or text documents.
    
-   Filter data to extract relevant lines or patterns.
    
-   Identify errors, warnings, or specific events in logs.
    
-   Perform batch operations on files using regular expressions.
    

The grep command is a versatile and efficient text-searching tool that greatly simplifies the process of finding patterns within files or streams. It is a crucial component of data analysis, debugging, and information retrieval in the Linux command line environment.

## **Linux Pipe Command: Connecting Commands for Data Processing**

The pipe command (|) in Linux allows you to connect the output of one command to the input of another, creating a data processing chain. This powerful feature enables you to combine multiple commands to perform complex operations, manipulate data, and streamline your workflow. Pipes facilitate efficient data transfer between commands, making it one of the key features of the Linux command line environment.

**Syntax:**

command1 | command2

**Examples:**

**Basic Command Chaining:**

**Command:**

ls -l | grep "file"

**Output:**

\-rw-r--r-- 1 user user 0 Aug 1 file1.txt

\-rw-r--r-- 1 user user 0 Aug 2 file2.txt

**Explanation:** The output of the ls -l command (list files in long format) is piped into grep to search for lines containing "file."

**Counting Matching Lines:**

**Command:**

cat data.txt | grep "pattern" | wc -l

**Input (data.txt):**

Line 1: This is a pattern.

Line 2: Another pattern here.

Line 3: No pattern in this line.

**Output:**

2

**Explanation:** The output of cat (display file contents) is piped to grep to filter lines containing "pattern," and then the output is piped to wc -l to count the lines.

**Sorting and Filtering:**

**Command:**

cat file.txt | sort | uniq

**Input (file.txt):**

apple

banana

apple

orange

banana

**Output:**

apple

banana

orange

**Explanation:** The output of cat is piped to sort to arrange lines alphabetically, and then the output is piped to uniq to remove duplicate lines.

**Combining Multiple Commands:**

**Command:**

ps aux | grep "firefox" | awk '{print $2}' | xargs kill -9

**Explanation:** This command chain lists all running processes (ps aux), filters for processes with "firefox" (grep), extracts the second column (process IDs) using awk, and then uses xargs to send the process IDs to the kill -9 command to forcefully terminate Firefox processes.

**Benefits and Use Cases:**

-   Efficiently process and manipulate data in a sequence of steps.
    
-   Perform complex data transformations and filtering.
    
-   Combine commands to generate customized reports.
    
-   Streamline tasks by connecting specialized commands.
    

The pipe command (|) is a fundamental feature of the Linux command line environment, enabling seamless integration of multiple commands to process, analyze, and manipulate data. It enhances efficiency and flexibility in data processing, making it an essential tool for various tasks.

## **Linux tee Command: Redirecting and Duplicating Output**

The tee command in Linux is used to read from standard input and write to both standard output and one or more files. It is particularly useful for capturing and saving the output of commands while still displaying it on the terminal. The tee command allows you to create log files, document processes, and share information with multiple destinations simultaneously.

**Syntax:**

command | tee \[options\] \[file...\]

**Common Options:**

\-a: appends output to files instead of overwriting.

\-i: ignores the interrupt signal (SIGINT), which is useful for avoiding interruptions while writing to files.

**Examples:**

**Creating a Log File:**

**Command:**

ls -l | tee list.txt

**Output (on terminal):**

total 0

drwxr-xr-x 1 user user 0 Aug 1 dir1

drwxr-xr-x 1 user user 0 Aug 2 dir2

**Content of list.txt:**

total 0

drwxr-xr-x 1 user user 0 Aug 1 dir1

drwxr-xr-x 1 user user 0 Aug 2 dir2

**Appending to a File:**

**Command:**

echo "New entry" | tee -a log.txt

**Content of log.txt (before):**

Entry 1

**Content of log.txt (after):**

Entry 1

New entry

**Duplicating Output to Multiple Files:**

**Command:**

ls | tee file1.txt file2.txt

**Content of file1.txt:**

file1.txt

file2.txt

**Content of file2.txt:**

file1.txt

file2.txt

**Benefits and Use Cases:**

-   Create log files while still seeing real-time output on the terminal.
    
-   Document command outputs and interactions for record-keeping.
    
-   Share command outputs with multiple individuals or processes.
    
-   Save the output of a command to a file and manipulate it further.
    

The tee command is a valuable utility for managing command output, logging activities, and efficiently distributing information to multiple destinations in the Linux command line environment. It enhances versatility and convenience in capturing and utilizing command output effectively.

## **Reading Summary**

In this reading, you have learned about:

-   Linux sort command
    
-   Linux head command: viewing the beginning of files
    
-   Linux tail command: viewing the end of files
    
-   Linux grep command: searching for text patterns
    
-   Linux pipe command: connecting commands for data processing
    
-   Linux tee command: redirecting and duplicating output




## **Reading Objective:**

In this reading, you will be able to understand the basic structure of a shell script, run the shell script, recognize wild cards, meta-characters, special variables, and use them to create simple shell scripts.

A Shell provides you with an interface to the Linux system. A shell script is a simple executable document that contains a sequence of commands that we might want to perform on a regular basis. By putting them into a shell script, we are reducing the job to just single command execution. Let’s look at some sample codes.

**Code**:

_1.#!/bin/bash_

_2.# Hello World Bash Shell Script_

_\# -----------------------------_

_\# print_

3.echo "Hello World”

_#End of the script_

## **Code Interpretation:**

Line1 is called a hashbang or shebang, it tells Linux that this script should be run through the /bin/bash shell. Linux flags line2 as a comment, and the rest of the line is completely ignored. In line3, we are printing “Hello World” on the terminal with the help of an echo command.

After saving the above file, we need to give it execute permission to make it runnable. If the filename is hello.sh then you can set the execute permission as follows:

_**chmod +x hello.sh**_

Now, execute the file using one of the following commands:

_**bash hello.sh**_

_**OR**_

_**./hello.sh**_

## **Wildcards**

A wildcard is a character that can be used as a substitute for any of a class of characters in a search, thereby greatly increasing the flexibility and efficiency of searches.

| 
**Wildcard**

 | 

**Meaning**

 | 

**Example**

 |
| --- | --- | --- |
| 

\*

 | 

It can represent zero or more number of characters

 | 

ls \*.html to list all the files in the current directory that have .html as extension

 |
| 

?

 | 

Represents exactly one character

 | 

ls ?? to list all the files in the current directory that have exactly two characters

 |
| 

\[\]

 | 

To represent any of the characters enclosed in the brackets

 | 

ls stat\[0-9\] to display all the filenames in the current directory with name stat followed by a digit

 |
| 

\[!\]

 | 

Match any single character not in the bracketed set

 | 

ls intro\[!a-z\] to display all the filenames in the current directory with the name intro followed by any character other than characters a to z

 |

Observe and understand the output of the following commands file \*, file s\*:

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/Qm81gff2TSi2cE_atqySJQ_76bbca481c4442b586c46c141c02d5a1_image.png)

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/e81HWLZiRO2feyUCOyNAaw_bf75ff45af80418eba9843ee8285b6a1_image.png)

Observe and understand the outputs of the following commands:

a. mv \*.jpg Pictures/

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/bbMx5369R76zAE9Q36MJ2g_fedb590f0c5b47febd395e1563cfa4a1_image.png)

b. mv \*.??? Pictures/

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/N7zW5rWjRKuq4invum7GJw_536fc54382744fefa5e729c9e41b26a1_image.png)

c. mv \*.\* Pictures/

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/YeVyiMlJRRGkjfBuqjVjGQ_6304cd3230b941afaa84cf56179692a1_image.png)

d. mv ????.jpg Pictures/

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/p9YT9XUkTtmkNsDp3ZPaVw_aa4d27d896a849e1870f272f497600a1_image.png)

Observe and understand the output of the following commands:

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/b3lk43YXSFiRKoGqKDLoXg_871f206bd65443ff98d66f8c87c35ea1_image.png)

a. ls file\*

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/sf9eVjkJR42xeD20B-iuWg_f4f5af52c3fb485a8ec4b012f93106a1_image.png)

b. ls file?

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/VAq3ZUwVSEW8M6JROv1Jvg_f9e55c711fb5417896d2a1113b6977a1_image.png)

Observe and understand the output of the following commands:

a. ls j\[aeiou\]m.txt

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/TbtjqKAPT6S_UHh4XJqzjQ_a626afde365346fd8994d5a608ba84a1_image.png)

b. ls j\[!aeiou\]?.txt

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/F4FjUbRjSmywPWSZXDeAEA_b7dd7e675e3746fd9bc61dd580c380a1_image.png)

## **Meta-characters**

The characters that have a special meaning attached to them.

| 
**Meta-character**

 | 

**Meaning**

 |
| --- | --- |
| 

\>

 | 

Output redirection (overwrite)

 |
| 

\>>

 | 

Output redirection (append)

 |
| 

<

 | 

Input redirection

 |
| 

\*

 | 

Substitution wildcard; zero or more characters

 |
| 

?

 | 

Substitution wildcard; one character

 |
| 

\[\]

 | 

Substitution wildcard; any character between brackets

 |
| 

|

 | 

Pipe

 |
| 

||

 | 

OR conditional execution

 |
| 

&&

 | 

AND conditional execution

 |
| 

#

 | 

Comment

 |
| 

$

 | 

Expand the value of a variable

 |
| 

\\

 | 

Escape interpretation of the next character

 |
| 

;

 | 

Command terminator

 |

Sometimes we might need to pass meta-characters to a Linux command and do not want the shell to interpret them. There are following two options to avoid shell interpretation of meta-characters:

a. Escape the meta-character with a backslash (\\). Example: echo \\$800 to print $800.

b. Use single quotes (' ') around a string. Example: echo $800" to print '$800 '.

Read the employee details file carefully. Observe and analyze the outputs.

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/CjXYjsPnRUee5K3Y9pZvnw_855006e661d44f66930e97b08dedb1a1_image.png)

a. By using output redirection, we can send the output to a file instead of showing it on the terminal.

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/yoC1_ynwTwOMnxgqMpvAUQ_6adb8a12f47e43d7acba13eb631f04a1_image.png)

b. After part (a), if we run wc employee\_details > employeecount.txt, then the contents of the file get overwritten.

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/_8PYCTlFRVuWWqYjdFPGbQ_f31be809402c42a79ec6cfa07a3b69a1_image.png)

c. After part (b), if we run sort employee\_details >> employeecount.txt, the output of this command gets appended to the already existing contents of the file.

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/y41Zso28REGjHQaFaHuArA_696657536cdf4ebcb85ffabd8ea835a1_image.png)

Observe and understand if there is any difference between cat file1 and cat < file1.

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/_TsQwtjnR7Sn0YiAJQ3C1Q_b2ab481a2544496f9c3e06dae6e511a1_image.png)

List all files and directories and give them as input to \`grep\` command using piping in Linux. Then, grep is listing those lines that contain the word “file.”

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/oiTUdL7UTUmZ1AlQb3Z8qQ_f1d733db17774d69bb955c119671cea1_image.png)

The command shell interprets the && as the logical AND. When using this command, the second command will be executed only when the first one has been successfully executed.

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/LKDBPh8FSLerQI10Rljcuw_e58c543ca2754fc7a129d032c50e32a1_image.png)

The || represents a logical OR. The second command is executed only when the first command fails.

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/Rkz0LB4JSXubbyqb72aS3g_2d87a1ffa9664d56bfa5b8d274d7b7a1_image.png)

We can execute multiple commands by separating them using “;”

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/B5M5OLBaS5KSNYmhRSVeFw_1a11176041d9479c9787ac5b580bbea1_image.png)

## **Special Variables:**

By using variables, we can make a script generic and apply it to various situations. Special variables are the ones that are reserved for some specific functions.

| 
**Special Variable**

 | 

**Description**

 |
| --- | --- |
| 

$0

 | 

The filename of the current script.

 |
| 

$n

 | 

"n" refers to a positive number that represents the nth argument passed to the script. For example, $1 represents the first argument. We can have nine such arguments in bash shell $0, $1, $2, ... $9.

 |
| 

$#

 | 

Represents the number of arguments passed to the script

 |
| 

$\*

 | 

Represents all the arguments passed to the script.

 |
| 

$?

 | 

Returns the exit status of the last command that was executed.

 |
| 

$!

 | 

Holds the process ID of the last background command.

 |
| 

$$

 | 

Represents the process ID of the current shell. For shell scripts, this is the process ID under which the scripts run.

 |
| 

$@

 | 

Represents all the arguments passed to the script.

 |

**Example Code**:

_#!/bin/bash_

_echo "Exit status usage"_

_cat file8_

_echo "Exit status of last command $?"_

_cat hello.sh_

_echo "Exit status of last command $?"_

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/QuOY209MQzCJk-R3wQyGuA_5513a00ebac041eb9403ce3b02e35ca1_image.png)

Observe and understand how the shell script responds to different options:

_cat> special\_variable.sh_

_#!/usr/bin/bash_

_echo "The total no of args are: $#"_

_echo "The script name is : $0"_

_echo "The first argument is : $1"_

_echo "The second argument is: $2"_

_echo "The third argument is: $3"_

_echo "The fourth argument is: $4"_

_echo "The total argument list is: $\*"_

a. ./special\_variable.sh 1 2

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/hTygqL46QvaCrlcL_njPfQ_d9fc83007a5841648c94c04b0677a7a1_image.png)

b. ./special\_variable.sh 1 2 3 4

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/ZAPO8e7FRFSsugqlPhAwFg_2f3ef2a3816e47ff9a7c8d04120f63a1_image.png)

c. ./special\_variable.sh 1 2 cat bat

![](Essential%20Reading%20Introduction%20to%20Shell%20Scripting%20%20Coursera/36di-pRASAK_ykIiGNNyHw_c069b48dd7df4850b66054264fb5e1a1_image.png)

## **Reading Summary**:

In this reading, you have learned the following:

-   Various ways in which the output of a command or shell script can change based on the usage of wildcards, meta-characters, and special variables



## **Topic: Example Codes**

## **Reading Objective:**

In this reading, you will understand several possible ways of writing shell scripts.

In this section, we will look at various example programs that will be using the concepts that we have learned so far.

**Example1**: Read two integer values as input from the user and perform basic mathematical operations on them.

#!/bin/bash

echo "enter value for a"

read a

echo "enter value for b"

read b

echo result of addition is

c=\`expr $a + $b\`

echo $c

echo result of subtraction is

c=\`expr $a - $b\`

echo $c

echo result of division is

c=\`expr $a / $b\`

echo $c

echo result of multiplication is

c=\`expr $a \\\* $b\`

echo $c

![](Essential%20Reading%20Example%20Codes%20%20Coursera/I6d4BFXUTIuV7u7_yybi9g_134be01dc436483dac485f284bae56a1_image.png)

**Example2**: Using arguments in shell script

#!/bin/bash

\# using arguments in a shell script

echo "My first name is $1"

echo "My last name is $2"

echo "Total number of arguments is $#"

![](Essential%20Reading%20Example%20Codes%20%20Coursera/JbrP0bViT96SNHFT5d9dzw_84b2ff14b1d143368f0ba24d6a9b42a1_image.png)

## **Reading Summary:**

In this reading, you have learned the following:

-   Different ways in which we can write programs using shell scripting



## **Reading Objective:**

In this reading, you will understand different ways in which we apply decision-making logic in shell scripts with some example codes.

Relational operators allow us to work with numerical values and with strings that are numbers in various useful ways. We can use them to compare numbers, thus helping us in statements that decision-making. The value that we receive after evaluation is 1 if the expression is true and 0 if false. Comparison expressions match lines where if the condition is true, then a particular action is performed.

**Relational Operators** in shell script

<table><tbody><tr><td><p><span><strong><span>Operator</span></strong></span></p></td><td><p><span><strong><span>Description</span></strong></span></p></td><td><p><span><strong><span>Usage</span></strong></span></p></td></tr><tr><td><p><span><span>-eq</span></span></p></td><td><p><span><span>Checks if the values of two operands are equal or not; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ $a -eq $b ]</span></span></p></td></tr><tr><td><p><span><span>-ne</span></span></p></td><td><p><span><span>Checks if the values of two operands are equal or not; if values are not equal, then the condition becomes true.</span></span></p></td><td><p><span><span>[ $a -ne $b ]</span></span></p></td></tr><tr><td><p><span><span>-gt</span></span></p></td><td><p><span><span>Checks if the value of the left operand is greater than the value of the right operand; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ $a -gt $b ]</span></span></p></td></tr><tr><td><p><span><span>-lt</span></span></p></td><td><p><span><span>Checks if the value of the left operand is less than the value of the right operand; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ $a -lt $b ]</span></span></p></td></tr><tr><td><p><span><span>-ge</span></span></p></td><td><p><span><span>Checks if the value of the left operand is greater than or equal to the value of the right operand; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ $a -ge $b ]</span></span></p></td></tr><tr><td><p><span><span>-le</span></span></p></td><td><p><span><span>Checks if the value of the left operand is less than or equal to the value of the right operand; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ $a -le $b ]</span></span></p></td></tr></tbody></table>

Boolean operators are used to perform various logical operations like AND, OR, and NOT. They are used as conjunctions to combine or exclude expressions for the purpose of decision-making.

**Boolean Operators** in shell script

<table><tbody><tr><td><p><span><strong><span>Operator</span></strong></span></p></td><td><p><span><strong><span>Description</span></strong></span></p></td><td><p><span><strong><span>Usage</span></strong></span></p></td></tr><tr><td><p><span><span>!</span></span></p></td><td><p><span><span>This is logical negation. This inverts a true condition into false and vice versa.</span></span></p></td><td><p><span><span>[ ! false ]</span></span></p></td></tr><tr><td><p><span><span>-o</span></span></p></td><td><p><span><span>This is logical OR. If one of the operands is true, then the condition becomes true.</span></span></p></td><td><p><span><span>[ $a -lt 10 -o $b -gt 50 ]</span></span></p></td></tr><tr><td><p><span><span>-a</span></span></p></td><td><p><span><span>This is logical AND. If both the operands are true, then the condition becomes true; otherwise false.</span></span></p></td><td><p><span><span>[ $a -lt 40 -a $b -gt 90 ]</span></span></p></td></tr></tbody></table>

String operators allow us to manipulate the values of variables in various useful ways without having to write complex programs or use some external UNIX utilities.

**String Operators** in shell script

<table><tbody><tr><td><p><span><strong><span>Operator</span></strong></span></p></td><td><p><span><strong><span>Description</span></strong></span></p></td><td><p><span><strong><span>Usage</span></strong></span></p></td></tr><tr><td><p><span><span>=</span></span></p></td><td><p><span><span>Checks if the values of two operands are equal or not; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ $a = $b ]</span></span></p></td></tr><tr><td><p><span><span>!=</span></span></p></td><td><p><span><span>Checks if the values of two operands are equal or not; if values are not equal, then the condition becomes true.</span></span></p></td><td><p><span><span>[ $a != $b ]</span></span></p></td></tr><tr><td><p><span><span>-z</span></span></p></td><td><p><span><span>Checks if the given string operand size is zero; if it is of zero length, then it returns true.</span></span></p></td><td><p><span><span>[ -z $a ]</span></span></p></td></tr><tr><td><p><span><span>-n</span></span></p></td><td><p><span><span>Checks if the given string operand size is non-zero; if it is of non-zero length, then it returns true.</span></span></p></td><td><p><span><span>[ -n $a ]</span></span></p></td></tr><tr><td><p><span><span>str</span></span></p></td><td><p><span><span>Checks if str is not the empty string; if it is empty, then it returns false.</span></span></p></td><td><p><span><span>[ $a ]</span></span></p></td></tr></tbody></table>

File test operators help us test many features of a file, such as whether it is readable or not, whether the user has write permissions on a file, the file size, whether the file exists or not, etc.

**File test operators** in shell script

<table><tbody><tr><td><p><span><strong><span>Operator</span></strong></span></p></td><td><p><span><strong><span>Description</span></strong></span></p></td><td><p><span><strong><span>Usage</span></strong></span></p></td></tr><tr><td><p><span><span>-d</span></span></p></td><td><p><span><span>Checks if the file is a directory; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ -d $file ]</span></span></p></td></tr><tr><td><p><span><span>-f</span></span></p></td><td><p><span><span>Checks if the file is an ordinary file; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ -f $file ]</span></span></p></td></tr><tr><td><p><span><span>-r</span></span></p></td><td><p><span><span>Checks if the file is readable; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ -r $file ]</span></span></p></td></tr><tr><td><p><span><span>-w</span></span></p></td><td><p><span><span>Checks if the file is writable; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ -w $file ]</span></span></p></td></tr><tr><td><p><span><span>-x</span></span></p></td><td><p><span><span>Checks if the file is executable; if yes, then the condition becomes true.</span></span></p></td><td><p><span><span>[ -x $file ]</span></span></p></td></tr><tr><td><p><span><span>-e</span></span></p></td><td><p><span><span>Checks if file exists; is true even if file is a directory but exists.</span></span></p></td><td><p><span><span>[ -e $file ]</span></span></p></td></tr></tbody></table>

**Test statement** is used to handle the true or false value returned by expressions. It uses certain operators to evaluate the condition on its right. It returns either a true or false exit status. If the given expression is true, test exits with a status of zero; otherwise, it exits with a status of 1. This can be used for making decisions.

**Example**: Numeric comparison using test

#!/bin/bash

\# usage of test expression on numeric values

echo Enter first number

read a

echo Enter second number

read b

\# using test command to check if numbers are equal

**test** $a -eq $b

echo "$? is the exist status for test a is equal to b"

![](Essential%20Reading%20Decision-Making%20in%20Shell%20Scripts%20%20Coursera/a67844ad-bf9c-4c0d-a905-f1de9d5cc921image1.png)

**Example**: String comparison using test

#!/bin/bash

\# Example to check if two strings are equal or not

echo Enter the first string

read a

echo Enter the second string

read b

**test** $a = $b

echo $? is the exit status for string comparison

![](Essential%20Reading%20Decision-Making%20in%20Shell%20Scripts%20%20Coursera/a67844ad-bf9c-4c0d-a905-f1de9d5cc921image2.png)

**Decision-making in shell script:** One of the most important parts of any programming language is the if-else statements. An if-else statement allows us to execute the conditional statements. We can use if-else in shell scripts when we want to check a particular condition, and then decide to execute a particular set of statements based on the result of this condition.

Let us have a look at the basic form of if statement.

**Basic Form**

**if** \[condition\]

then

statement1

**fi**

In the simple form, if the condition succeeds, the statements within the if block are executed; otherwise, this code block will not be executed.

**Example**: Shell script to check if the first number is less than the second number

#!/bin/bash

echo "Enter first number"

read a

echo "Enter second number"

read b

#check if variable a is less than b

**if** \[ $a -lt $b \]

**then**

echo "a is less than b"

**fi**

![](Essential%20Reading%20Decision-Making%20in%20Shell%20Scripts%20%20Coursera/a67844ad-bf9c-4c0d-a905-f1de9d5cc921image3.png)

**Example**: Shell script to show basic string operations

#!/bin/bash

echo "Enter your name"

read name

echo "Enter your friend's name"

read othername

\# to check if the string length is non-zero

**if** \[\[ -n ${name} \]\]

**then**

echo "length of the string is non-zero"

**fi**

\# to check if the string length is zero

**if** \[\[ -z ${name} \]\]

**then**

echo "length of the string is zero"

**fi**

\# check two if the two string are equal

**if** \[\[ ${name} = ${othername} \]\]

**then**

echo "both the string are equal"

**fi**

\# check if the two string are not equal

**if** \[\[ ${name} != ${othername} \]\]

**then**

echo "both the string are not equal"

**fi**

![](Essential%20Reading%20Decision-Making%20in%20Shell%20Scripts%20%20Coursera/a67844ad-bf9c-4c0d-a905-f1de9d5cc921image4.png)

**Example**: Shell script to demonstrate the usage of logical operators

#!/bin/bash

echo "Enter your marks to know the grade"

read a

#check if variable a is less than or equal to 100 AND greater than and equal to 80

#logical operator –a(AND) is used here

**if** \[ $a -le 100 -a $a -ge 80 \]

**then**

echo "Your grade is A"

**fi**

#check if variable a is less than 80 AND greater than and equal to 60

#logical operator –a(AND) is used here

**if** \[ $a -lt 80 -a $a -ge 60 \]

**then**

echo "Your grade is B"

**fi**

#check if variable a is less than 60 AND greater than and equal to 40

#logical operator –a(AND) is used here

**if** \[ $a -lt 60 -a $a -ge 40 \]

**then**

echo "Your grade is C"

**fi**

#check if variable is equal to 0 OR variable a is less than 40

#logical operator –o(OR) is used here

**if** \[ $a -eq 0 -o $a -lt 40 \]

**then**

echo "Your grade is fail"

**fi**

![](Essential%20Reading%20Decision-Making%20in%20Shell%20Scripts%20%20Coursera/a67844ad-bf9c-4c0d-a905-f1de9d5cc921image5.png)

**Example**: Shell script to show usage of file test operators

#!/bin/bash

echo "Enter a complete filename"

read file

#check read permission of file

**if** \[ -r $file \]

**then**

echo "File has read access"

**fi**

#check write permission of file

**if** \[ -w $file \]

**then**

echo "File has write permission"

**fi**

#check execute permission of file

**if** \[ -x $file \]

**then**

echo "File has execute permission"

**fi**

#check if file is a normal file

**if** \[ -f $file \]

**then**

echo "File is an ordinary file"

**fi**

#check if file is a directory

**if** \[ -d $file \]

**then**

echo "File is a directory"

**fi**

#check if the file exists

**if** \[ -e $file \]

**then**

echo "File exists"

**fi**

![](Essential%20Reading%20Decision-Making%20in%20Shell%20Scripts%20%20Coursera/a67844ad-bf9c-4c0d-a905-f1de9d5cc921image6.png)

## **Reading Summary:**

In this reading, you have learned:

-   Different ways in which we can write programs using basic if statement, test expressions, and various types of operators



## **Reading Objective:**

In this reading, you will understand different ways in which we can apply the logic for iterative constructs.

Loops are used to repeatedly execute the statements following the test expression if a condition is true. Loops are often used to iterate through the fields within a record.

**for loop:** It requires three expressions within the parentheses: the initialization expression, the test expression, and the expression to update the variables within the test expression.

Let us look at different ways in which we can use for loop

| 
1

 | 

2

 | 

3

 |
| --- | --- | --- |
| 

_**foreach**_ _var (wordlist)_

_commands_

_**end**_

 | 

_**for**_ _var_ _**in**_ _wordlist_

_**do**_

_commands_

_**done**_

 | 

_**for**_ _( x = 3; x <= n; x++ )_

_commands_

 |

**Example:** Let us look at a very simple implementation of for loop

_#!/bin/bash_

_#simple for loop iteration_

_**for**_ _i_ _**in**_ _1 2 3 4 5_

_**do**_

_echo "Welcome $i times"_

_**done**_

![](Essential%20Reading%20Looping%20Constructs%20%20Coursera/xMhMMhk4QtSzYcZ2R0jbKw_b713269101ec45e085d58b7d6b5caea1_image.png)

**Example:** Let us print a table of a given number using for loop

_#!/bin/bash_

_#Script to print table of a number_

_#check if argument is provided if not print number missing and then exit_

_**if**_ _\[ $# -eq 0 \]_

_**then**_

_echo "Error - Number missing form command line argument"_

_echo "Syntax : $0 number"_

_echo "Use to print multiplication table for given number"_

_exit 1_

_**fi**_

_#print the table for the given number_

_n=$1_

_**for**_ _i_ _**in**_ _1 2 3 4 5 6 7 8 9 10_

_**do**_

_echo "$n \* $i = \`expr $i \\\* $n\`"_

_**done**_

![](Essential%20Reading%20Looping%20Constructs%20%20Coursera/GVC8lgwlR3uFw_kHyf4rXw_1363b23134854c8c9b0214018b79bea1_image.png)

**Example**: Script using for loop

_#!/bin/bash/_

_\# set counter 'c' to 1 and check condition if c is less than or equal to 5_

_\# the loop will keep on repeating c becomes greater than 5_

_**for**__( c=1; c<=5; c++ )_

_**do**_ 

   _echo "Welcome $c times"_

_**done**_

![](Essential%20Reading%20Looping%20Constructs%20%20Coursera/YTZM08YdSYi1ju2IFU82-w_e86bc986e0e54d86955ce378e33f8fa1_image.png)

**While loop**: The first step in using a while loop is to set a variable to an initial value. The value is then tested in the while expression. If the expression evaluates to true (nonzero), the body of the loop is entered and the statements within that body are executed.

Let us look at different ways in which we can use while loop

| 
1

 | 

2

 |
| --- | --- |
| 

_**while**_ _(expression)_

_commands_

_**end**_

 | 

_**while**_ _command_

_**do**_

_command_

_**done**_

 |

**Example:** Let us look at a very simple example of while loop

_#!/bin/bash_

_#simple usage of while loop_

_number=0_

_**while**_ _\[ $number -lt 10 \]_

_**do**_

_echo "Number = $number"_

_number=\`expr $number + 1\`_

_**done**_

![](Essential%20Reading%20Looping%20Constructs%20%20Coursera/YvAVuj_ISHmKs-VTOffhZg_d496bc38d56843018053b555583bada1_image.png)

**Example**: This shell script prints the multiplication table for a given number using while loop

_#!/bin/sh_

_#Script to print table for a given number_

_#check if input number is provided or not. If not then print a message and exit from the program_

_**if**_ _\[ $# -eq 0 \]_

_**then**_

_echo "Error - Number missing form command line argument"_

_echo "Syntax : $0 number"_

_echo " Use to print multiplication table for given number"_

_exit 1_

_**fi**_

_#print the table_

_n=$1_

_i=1_

_**while**_ _\[ $i -le 10 \]_

_**do**_

_echo "$n \* $i = \`expr $i \\\* $n\`"_

_i=\`expr $i + 1\`_

_**done**_

![](Essential%20Reading%20Looping%20Constructs%20%20Coursera/RjcqFqFuSFustreWytW3Pw_362ea190f3dc41e79e35d377f63abfa1_image.png)

**Example**: Script to print the sum of the digits of a given number using while loop

_#!/bin/bash_

_#Script to print the sum of the digits of a number_

_echo "Enter a number"_

_read num_

_sum=0_

_**while**_ _\[ $num -gt 0 \]_

_**do**_

_mod=$((num % 10)) #It will split each digits_

_sum=$((sum + mod)) #Add each digit to sum_

_num=$((num / 10)) #divide num by 10._

_**done**_

_echo Sum of the digits is $sum_

![](Essential%20Reading%20Looping%20Constructs%20%20Coursera/h_26r_cgQ06rmzgr9Vvs0A_49965fcf94cd40dbbabaf5c22e392ca1_image.png)

**Until loop:** It is used to iterate over a block of commands until the required condition is false. First, the condition is checked if the condition is false, then executes the statements and keeps on repeating this. But once the condition becomes true, the program control moves to the next command in the script.

_**until**_ _\[ condition \];_

_**do**_

_block-of-statements_

_**done**_

**Example**: Script to print the value of variable i until it becomes equal to 1. We start with value i=10 and then keep on decreasing it by 1.

_#!/bin/bash_

_#script to print the value of i until it becomes 1_

_echo "until loop"_

_i=10_

_**until**_ _\[ $i == 1 \]_

_**do**_

_echo "$i is not equal to 1";_

_i=$((i-1))_

_**done**_

_echo "i value is $i"_

_echo "loop terminated"_

## **Break and Continue Statements:**

The break statement is used to terminate the execution of the entire loop after completing the execution of all of the lines of code up to the break statement. It then steps down to the code following the end of the loop.

The continue statement is similar to the break command, except that it causes the current iteration of the loop to exit, rather than the entire loop. This statement is useful when an error has occurred but you want to try to execute the next iteration of the loop.

**Example**: Script to identify even and odd numbers using for loop and continue statement

_NUMS="1 2 3 4 5 6 7"_

_**for**_ _Num in $NUMS_

_**do**_

_Q=\`expr $Num % 2\`_

_**if**_ _\[ $Q -eq 0 \]_

_**then**_

_echo "$Num is an even number!!"_

_**continue**_

_**fi**_

_echo "$Num is odd number"_

_**done**_

![](Essential%20Reading%20Looping%20Constructs%20%20Coursera/MLnTZy2hQ0mOO2xaB74vQg_431d4aec2f6c4d0dbbe99a7a7e2580a1_image.png)

**Example**: We are using for loop to iterate over values from 1 to 10. Inside the loop, we are using the echo command to print the value of variable i. We also have an if statement that checks if the value of i is equal to 5. If it is, then we use break statement to exit the loop. As a result, when the program is run, it will print values 1 through 5 and then terminate the loop.

_#!/bin/bash/_

_#usage of break statement_

_i=1_

_**while**_ _\[ $i -le 10 \]_

_**do**_

_echo $i_

_if \[ $i -eq 5 \]_

_**then**_

_**break**_

_**fi**_

_\# (( ... )) construct permits arithmetic expansion and evaluation._

_i=$((i+1))_

_**done**_

![](Essential%20Reading%20Looping%20Constructs%20%20Coursera/6hkEfYDIQkmg-J4EDdhViw_05ea6432cc424111842d560f4341ffa1_image.png)

## **Reading Summary:**

In this reading, you have learned:

-   Various ways in which we can write programs using for, while, and until loops
    
-   The change of control in loops using break and continue statements


## **Reading Objective:**

In this reading, you will understand ways in which we can take input from files, store outputs in files, and manipulate files one line at a time in a shell script.

A lot of time, we use shell scripting to interact with the files. Shell scripting offers some operators and commands to check different properties associated with the file. Now, let us focus on performing different functions on file using shell scripts.

If you need to read each line from a file and perform some action with it, then you can use “while” loop. In the syntax given below, replace “\[commands\]” section with whatever actions you want to perform on the input file and replace “\[INPUT\_FILE\]” with the appropriate input file name.

**Syntax**:

_**while**_ _read line_

_**do**_

_\[COMMAND\]_

_**done**_ _< \[INPUT\_FILE\]_

**Example**: Create a text file called integernos.txt and store some random numbers in it (one number in one line). Write a shell script program to display all the even numbers from this file.

_#!/bin/bash/_

_**while**_ _read line_

_**do**_

_x=\`expr $line % 2\` #test for even number_

_**if**_ _\[$x ‐eq 0\]_

_**then**_

_echo $line #display even numbers_

_**fi**_

_**done**_ _< integernos.txt #input file_

![](Essential%20Reading%20File%20Handling%20%20Coursera/fg1_i0R_Q66PxteCOtsT6g_b2b25197224f4b2ea2bb1a4bc58fdda1_image.png)

**Example**: Script to read file character by character.

_#!/bin/bash_

_read -p "Enter file name : " filename_

_**while**_ _read -n1 character_

_**do**_

_echo $character_

_**done**_ _< $filename_

![](Essential%20Reading%20File%20Handling%20%20Coursera/1eYegYKIQQ2e-JDl_I224g_1eef29f0e84b4a0ab0bdb4e46a997aa1_image.png)

**Example**: Copy the odd lines of the file named data.txt to a file named odd.txt and copy the even lines of this file to a file named even.txt

_#!/bin/bash/_

_i=1_

_**while**_ _read line_

_**do**_

_x=\`expr $i % 2\` #test for even number_

_echo $x_

_**if**_ _\[ $x -eq 0 \]_

_**then**_

_echo $line >> even.txt_

_**else**_

_echo $line >> odd.txt_

_**fi**_

_i=\`expr $i + 1\`_

_**done**_ _< text.txt #input file_

![](Essential%20Reading%20File%20Handling%20%20Coursera/2cvMEL4lR5OEK-39rDX9nw_f6319b2e6e6941f68a082434f92a55a1_image.png)

![](Essential%20Reading%20File%20Handling%20%20Coursera/fYj89u2zQ8WTX8sUpSaW0Q_da48defa1e364fa8af1cf30a392071a1_image.png)

![](Essential%20Reading%20File%20Handling%20%20Coursera/YOXdqIEcRIO_pWqLB_cnvA_61b548a87b37443fb9bf9dad70a12aa1_image.png)

## **Reading Summary:**

In this reading, you have learned:

-   Ways in which we can use files as input or output in shell scripts






The solutions for practice lab, along with the HTML file in module 8, can be accessed through the resource tab of the course. Please click on the below link, which will redirect you to the corresponding folder.

[https://www.coursera.org/learn/command-line-interface-and-scripting/resources/travv](https://www.coursera.org/learn/command-line-interface-and-scripting/resources/travv)




## **Reading Objective:**

In this reading, you will be able to understand the dual mode operation that is used in Linux operating systems for the safety of the programs, process, and its lifecycle, and some basic process-related system calls.

## **Main Reading Section:**

A system call is just what its name implies, a request for the operating system to do something on behalf of the user’s program. In computing, a system call is how a program requests a service from an operating system’s kernel. It provides an essential interface between a process and the operating system.

**Dual-Mode Operation**: Sharing system resources requires the operating system to ensure that an incorrect program cannot cause other programs to execute incorrectly. One of the ways of protecting the programs in an operating system is by using two different modes.

-   User mode: execution is done on behalf of a user. It is a restricted mode that limits access to system resources.
    
-   Kernel mode (monitor mode or system mode): execution done on behalf of the operating system. It is a privileged mode that allows access to system resources.
    

One of the ways to implement these two modes is by using a mode bit. When the value of the mode bit is 0, it is in monitor mode, but when the value is 1, it is in user mode.

When a user-level application needs to perform an operation that requires kernel mode access, such as accessing hardware devices or modifying system settings, it must make a system call to the operating system kernel. The operating system switches the processor from user mode to kernel mode to execute the system call and then switches back to user mode once the operation is complete.

![](Essential%20Reading%20Linux%20OS%E2%80%94Working%20Modes%20%20Coursera/Cxv_HFZCQzOGhLe_PH1s0w_4d56cf59711e4db2ac26a12933df5da1_image.png)

**Process:** A process is a program in execution. It consists of the data read from files, input from a user, program instructions, and many more. A process in Linux starts every time you start an application or run a program or command. The lifecycle of the process is shown as follows:

![](Essential%20Reading%20Linux%20OS%E2%80%94Working%20Modes%20%20Coursera/dkZ0H_yCSSy1YLULqaIS3w_95589941828141a8b28881d2d38759a1_image.png)

Initially, when the process is created, it enters the **new** state. Then, the operating system will allocate and initiate a process control block and some initial resources for this process. This is when it is admitted and is **ready** to start executing, but it is not actually executing on the CPU. Once the scheduler allocates the CPU to the ready process, it goes into the **running** state. The running process can be interrupted so that the context switch can be performed; this will move the running process back into the ready state. The running process might want to initiate some longer operations like reading data from the disk or waiting for some event; this is when it is moved to the **waiting** state. Once the I/O operation or event is complete, the process goes back to the ready state. When all the tasks of the process are complete or the process encounters any error, it needs to exit with an appropriate exit status and move to the **terminated** state.

**fork()**: A new process is created by the fork() system call. This function creates a new copy called the child out of the original process that is called the parent. When the parent process closes or crashes for some reason, it also kills the child process.

**exit()**: The exit() system call is used by a program to terminate its execution. The operating system reclaims resources that were used by the process after the exit() system call.

**wait()**: It blocks the calling process until one of its child processes exits or a signal is received. After the child process terminates, the parent continues its execution after the wait system call instruction.

**waitpid()**: It suspends execution of the current process until a child specified by the pid argument has changed state.

**exec()**: This family of functions replaces the current process image with a new process image. It loads the program into the current process space and runs it from the entry point. fork starts a new process, which is a copy of the one that calls it, whereas exec replaces the current process image with another one. Both parent and child processes are executed simultaneously in case of fork(), and control never returns to the original program unless there is an exec() error. Some of its variations are:

int execl(const char \*path, const char \*arg, ...);

int execlp(const char \*file, const char \*arg, ...);

int execv(const char \*path, char \*const argv\[\]);

int execvp(const char \*file, char \*const argv\[\]);

**Example**: This program shows that by using wait, the parent process will wait for the child to complete.

_#include <sys/types.h>_

_#include <sys/types.h>_

_#include <stdio.h>_

_#include <unistd.h>_

_#include <sys/wait.h>_

_int main(int argc, char \*argv\[\]) {_

_/\* fork a child process \*/_

_pid\_t pid = fork();_

_if (pid < 0) { /\* error occurred \*/_

_fprintf(stderr, "\*\*\*\*Failure of fork system call\*\*\*\*");_

_return 1;_

_}_

_else if (pid == 0) { /\* child process \*/_

_printf("I'm the child process \\n"); /\* you can execute some commands here \*/_

_}_

_else { /\* parent process \*/_

_/\* parent will wait for the child to complete \*/_

_wait(NULL);_

_/\* When the child is ended, then the parent will continue to execute its code \*/_

_printf("Child process is now complete \\n");_

_}_

_}_

![](Essential%20Reading%20Linux%20OS%E2%80%94Working%20Modes%20%20Coursera/f7d3dc0c-ef6f-49f4-9385-0d3ec6478479_8d4babe3d1904572919fbd0db36d155b_6035f0e3-ccd9-49d6-842a-7b120a4baf23image2.png)

**Example**: Print the process IDs for parent and child.

_#include <stdio.h>_

_#include <stdlib.h>_

_#include <sys/types.h>_

_#include <sys/wait.h>_

_#include <unistd.h>_

_int main(void) {_

_//using fork() function to create a child process from the main process_

_pid\_t pid = fork();_

_if(pid == 0) {_

_//printing the process ID and the parent ID i.e. PID and PPID respectively_

_printf("Child => PPID: %d PID: %d\\n", getppid(), getpid());_

_exit(EXIT\_SUCCESS); //exit() is used on the child process to finish the execution of the child process_

_}_

_else if(pid > 0) {_

_//printing the process ID i.e. PID_

_printf("Parent => PID: %d\\n", getpid());_

_printf("Waiting for child process to finish.\\n");_

_wait(NULL); //wait (NULL) on the parent process is used to wait for the child process to get finished._

_printf("Child process finished.\\n");_

_}_

_else {_

_printf("Unable to create child process.\\n");_

_}_

_return EXIT\_SUCCESS;_

_}_

![](Essential%20Reading%20Linux%20OS%E2%80%94Working%20Modes%20%20Coursera/724cb57f-92e9-47db-aa82-6922d971627c_1e18e897edde41da9186f8342f079fe2_6035f0e3-ccd9-49d6-842a-7b120a4baf23image3.png)

**Example**: Code to demonstrate the use of waitpid().

_#include<stdio.h>_

_#include<stdlib.h>_

_#include<sys/wait.h>_

_#include<unistd.h>_

_void waitdemo()_

_{_

_int i, stat;_

_pid\_t pid\[5\];_

_for (i=0; i<5; i++)_

_{_

_if ((pid\[i\] = fork()) == 0)_

_{_

_sleep(1);_

_exit(100 + i);_

_}_

_}_

_// Using waitpid() and printing exit status of children._

_for (i=0; i<5; i++)_

_{_

_pid\_t cpid = waitpid(pid\[i\], &stat, 0);_

_if (WIFEXITED(stat))// WIFEXITED(status): child exited normally_

_printf("Child %d terminated with status: %d\\n",_

_cpid, WEXITSTATUS(stat));// WEXITSTATUS(status): return code when child exits_

_}_

_}_

_// main code_

_int main()_

_{_

_waitdemo();_

_return 0;_

_}_

![](Essential%20Reading%20Linux%20OS%E2%80%94Working%20Modes%20%20Coursera/bfb25f1c-cd34-4937-be83-023ef68f0119_1382557b2c3642878bb38c4fdd87d425_6035f0e3-ccd9-49d6-842a-7b120a4baf23image4.png)

**Example**: Demo of exec command.

_demo.c_

_#include <stdio.h>_

_#include <unistd.h>_

_#include <stdlib.h>_

_int main(int argc, char \*argv\[\])_

_{_

_printf("PID of demo.c = %d\\n", getpid());_

_char \*args\[\] = {"Hello", "Linux", "system", NULL};_

_execv("./hello", args);_

_printf("Back to demo.c");_

_return 0;_

_}_

_Hello.c_

_#include <stdio.h>_

_#include <unistd.h>_

_#include <stdlib.h>_

_int main(int argc, char \*argv\[\])_

_{_

_printf("We are in Hello.c\\n");_

_printf("PID of hello.c = %d\\n", getpid());_

_return 0;_

_}_

_When we run demo.c we get the following output:_

_PID of demo.c = 4733_

_We are in Hello.c_

_PID of hello.c = 4733_

## **Reading Summary:**

In this reading, you have learned the following:

-   The concept of the kernel and user mode, the working of system calls, and the concept of process
    
-   How to use process-related system calls like fork(), wait(), waitpid(), exit(), and exec()




## **Reading Objective:**

In this reading, you will be able to understand the concept of signals, signal handlers, and how system calls are different from function calls.

## **Main Reading Section:**

**signal()**: Signals are a technique used to notify a process that some condition has occurred. A signal is a message or notification issued to a program by the operating system or another application.

Each signal may have a signal handler, which is a function that gets called when the process receives that signal. The function is called in “asynchronous mode,” meaning that nowhere in your program you have code that calls this function directly. Instead, when the signal is sent to the process, the operating system stops the execution of the process and “forces” it to call the signal handler function. When that signal handler function returns, the process continues execution from where it left.

A process can also explicitly send signals to itself or to another process. raise() and kill() functions can be used for sending signals. Both functions are declared in signal.h header file in C.

-   **raise()**: sends a signal to the calling thread.
    
-   **kill()**: sends a signal to a specified process, to all members of a specified process group, or to all processes on the system. It takes two arguments. The first, pid, is the process ID you want to send a signal to, and the second, sig, is the signal you want to send.
    

## **Signal Handler**:

For our convenience, there are two pre-defined signal handler functions that we can use, instead of writing our own: SIG\_IGN and SIG\_DFL.

SIG\_IGN: causes the process to ignore the specified signal.

SIG\_DFL: causes the system to set the default signal handler for the given signal.

You can register your own signal handler by using signal() interface, which is the oldest one. It takes two arguments: a reference to a signal handler code and a signal number.

**Example:** User-defined signal handler.

_// User-defined Signal Handler in C language_

_#include<stdio.h>_

_#include<signal.h>_

_// Handler for SIGINT, caused by action: “Ctrl-C at keyboard”_

_void handle\_sig(int sig)_

_{_

_printf("Caught a signal %d\\n", sig);_

_}_

_int main()_

_{_

_signal(SIGINT, handle\_sig);//when user presses Clt-C signal will be caught_

_while (1) ;//infinite loop_

_return 0;_

_}_

**Example:** Using raise() system calls.

_#include<stdio.h>_

_#include<signal.h>_

_void sig\_handler(int signum){_

_printf("Inside my custom handler function\\n");_

_}_

_int main(){_

_signal(SIGUSR1,sig\_handler); // Register the signal handler_

_printf("Inside the main function\\n");_

_raise(SIGUSR1);// process send SIGUSR1 signal to itself using raise() function_

_printf("Back to main function\\n");_

_return 0;_

_}_

![](Essential%20Reading%20Signals%20and%20Handling%20%20Coursera/50ssI4FHSmmptsGBqJJy1Q_a449f4d346b14208b5ed566aff73e6a1_image.png)

**Example:** Using kill to send signals.

_#include<stdio.h>_

_#include <unistd.h>_

_#include<signal.h>_

_void sig\_handler(int signum){_

_printf("This is my custom handler function\\n");_

_}_

_int main(){_

_pid\_t pid;_

_signal(SIGUSR1,sig\_handler); // Register the signal handler_

_printf("This is my main function\\n");_

_pid=getpid(); //get the Process ID of self_

_kill(pid,SIGUSR1);// process sens SIGUSR1 signal to itself using kill() function_

_printf("I am back to my main function\\n");_

_return 0;_

_}_

![](Essential%20Reading%20Signals%20and%20Handling%20%20Coursera/TFgkcK6kTwGcKWwY0m-clA_6f29a688c45e41fe9783d08770ae0da1_image.png)

**Example**: Parent and child communication using kill and signal.

_#include<stdio.h>_

_#include <unistd.h>_

_#include <stdlib.h>_

_#include<signal.h>_

_void sig\_handler\_parent(int signum){_

_printf("Parent : Received a response signal from child \\n");_

_}_

_void sig\_handler\_child(int signum){_

_printf("Child : Received a signal from parent \\n");_

_sleep(1);_

_//the child process sends another SIGUSR1 signal to parent and getppid()_

_//function is used for getting parent process ID._

_kill(getppid(),SIGUSR1);_

_}_

_int main(){_

_pid\_t pid;_

_//fork() function creates child process and return zero to child process and child //process ID to parent process._

_if((pid=fork())<0){ //create child and check for failure_

_printf("Fork Failed\\n");_

_exit(1);_

_}_

_/\* Child Process \*/_

_else if(pid==0){_

_//when signal is received from the parent, handler function is invoked_

_signal(SIGUSR1,sig\_handler\_child); // Register signal handler_

_printf("Child: waiting for signal\\n");_

_//waiting for signal from parent_

_pause();_

_}_

_/\* Parent Process \*/_

_else{_

_signal(SIGUSR1,sig\_handler\_parent); // Register signal handler_

_//it is slept for 1 second so that child process can register signal handler_

_//function and wait for the signal from parent._

_sleep(1);_

_printf("Parent: sending signal to the Child\\n");_

_//After 1 second parent process send SIGUSR1 signal to child process and wait_

_//for the response signal from child._

_kill(pid,SIGUSR1);_

_printf("Parent: waiting for the response\\n");_

_pause();_

_}_

_return 0;_

_}_

![](Essential%20Reading%20Signals%20and%20Handling%20%20Coursera/Z8JZQTVpTs6y0UcpzxIKgA_480b66d1dcef44ad93841aba36c40ba1_image.png)

How are system calls different from function calls?

-   System call involves context switching (from user to kernel and back), whereas function call does not.
    
-   System calls take much longer time than function calls.
    
-   Most of the system calls return a value (error if failed), whereas it is not necessary for function calls.
    
-   Avoiding excessive system calls might be a wise strategy for programs that need to be tightly optimized.
    

## **Reading Summary:**

In this reading, you have learned the following:

-   The concept of a signal, signal handler, with examples using kill(), and raise() signals





The solutions for the practice lab, along with the HTML file in module 9, can be accessed through the resource tab of the course. Please click on the below link, which will redirect you to the corresponding folder.

[https://www.coursera.org/learn/command-line-interface-and-scripting/resources/qXoB8](https://www.coursera.org/learn/command-line-interface-and-scripting/resources/qXoB8)




## **Reading Objective:**

In this reading, you will be able to understand file input output-related system calls.

## **Main Reading Section:**

System calls are essential components of the operating system Linux because they enable user-space programs to perform privileged activities in a controlled and safe manner. File management system calls are used to open, read, write, and close documents, as well as to create, rename, and delete them.

-   open(): It is the system call to open a file to perform operations such as read and write
    
-   read(): This system call opens the file in reading mode. We cannot edit the files with this system call. Multiple processes can execute the read() system call on the same file simultaneously.
    
-   write(): It is an internal call that is used to write information stored in a buffer of memory. We cannot edit the files with this system call. Multiple processes can execute the read() system call on the same file simultaneously.
    
-   close(): It is a system call for closing a file determined by a given file descriptor.
    
-   creat(): It creates a new empty file on the disk. It returns the file descriptor assigned to the file on success, whereas it returns -1 upon failure.
    
-   lseek(): It is a system call that repositions the read/write file offset, i.e., it changes the positions of the read/write pointer within the file.
    

## **System Call Usage**:

-   int creat(char \*filename, mode\_t mode): filename is used to specify the name of the file which you want to create and mode indicates permissions of a new file. It returns the file descriptor used, whereas it returns -1 upon failure.
    
-   int open (const char\* Path, int flags \[, int mode \]): path to the file which you want to use. Flags can take the following values: O\_RDONLY: read-only, O\_WRONLY: write only, O\_RDWR: read and write, O\_CREAT: create the file if it does not exist, and O\_EXCL: prevent creation if it already exists. It returns the file descriptor used, whereas it returns -1 upon failure.
    
-   int close(int fd): fd represents the file descriptor of the file that we want to close. It returns 0 on success and -1 on failure
    
-   size\_t read (int fd, void\* buf, size\_t cnt): fd is the file descriptor, buf is the buffer to read the data from, and cnt is the requested number of bytes to read. It returns the number of bytes read on success, returns 0 on reaching the end of the file, and returns -1 on error.
    
-   size\_t write (int fd, void\* buf, size\_t cnt): fd is the file descriptor, buf is the buffer to write the data to, and cnt is the requested number of bytes to write. It returns the number of bytes written successfully, returns 0 on reaching the end of the file, and returns -1 on error.
    
-   Off\_t lseek(int fd, off\_t offset, int whence): The first parameter “fd” is a file descriptor. The second is “offset,” which is used to position the pointer. The third parameter, “whence,” is used to specify the position of a file pointer, e.g., beginning, end, and mid. lseek(fd,5,SEEK\_SET): This moves the pointer 5 positions ahead starting from the beginning of the file. lseek(fd,5,SEEK\_CUR): This moves the pointer 5 positions ahead from the current position in the file. lseek(fd,-5,SEEK\_CUR): This moves the pointer 5 positions back from the current position in the file. lseek(fd,-5,SEEK\_END): This moves the pointer 5 positions back from the end of the file.
    

**Example**: C program to show open system call.

_#include<stdio.h>_

_#include<fcntl.h>_

_#include<errno.h>_

_extern int errno;_

_int main()_

_{_

_// if the file does not exist in the current directory, then file demo.txt is created._

_int fd = open("demo.txt", O\_RDONLY | O\_CREAT);_

_printf("fd = %d/n", fd);_

_if (fd ==-1)_

_{_

_// print which type of error has occurred_

_printf("Error Number % d\\n", errno);_

_// print program detail"Success or failure"_

_perror("Program");_

_}_

_return 0;_

_}_

**Sample Output:**

fd = 3

**Example**: Demonstrate the close system call.

_#include<stdio.h>_

_#include<fcntl.h>_

_int main()_

_{_

_// assuming that demo.txt is already created_

_int fd1 = open("demo.txt", O\_RDONLY, 0); //open file in read-only mode_

_close(fd1); //close system call just takes the file descriptor as parameter_

_// assuming test.txt is already created_

_int fd2 = open("baz.txt", O\_RDONLY, 0); //open file in read-only mode_

_printf("fd2 = % d\\n", fd2);_

_exit(0);_

_}_

**Output:**

fd2 = 3

**Example**: C program to illustrate the read system call.

_#include<stdio.h>_

_#include <fcntl.h>_

_int main()_

_{_

_int fd, sz;_

_char \*c = (char \*) calloc(100, sizeof(char));_

_fd = open("demo.txt", O\_RDONLY); //open file in read-only mode_

_if (fd < 0) { perror("r1"); exit(1); } //check for error in opening_

_sz = read(fd, c, 10); //read 10 bytes from the opened file_

_printf("called read(% d, c, 10). returned that"_

_" %d bytes were read.\\n", fd, sz);_

_c\[sz\] = '\\0';_

_printf("Those bytes are as follows: % s\\n", c);_

_}_

**Output:**

called read(3, c, 10). returned that 10 bytes were read.

Those bytes are as follows: 0 0 0 demo.

**Example**: C program to illustrate the write system call.

_#include<stdio.h>_

_#include <fcntl.h>_

_main()_

_{_

_int sz;_

_int fd = open("demo.txt", O\_WRONLY | O\_CREAT | O\_TRUNC, 0644); //open demo.txt_

_//in write mode and create the file if it doesn’t exist, O\_TRUNC will truncate_

_//the file and 0644 represents permissions_

_if (fd < 0) //check for errors_

_{_

_perror("r1");_

_exit(1);_

_}_

_sz = write(fd, "hello friends\\n", strlen("hello friends\\n"));_

_printf("called write(% d, \\"hello friends\\\\n\\", %d)."_

_" It returned %d\\n", fd, strlen("hello friends\\n"), sz);_

_close(fd);_

_}_

**Output:**

called write(3, "hello friends\\n", 14). It returned 13

**Example**: C program to illustrate open, write, and close I/O system calls.

_#include<stdio.h>_

_#include<string.h>_

_#include<unistd.h>_

_#include<fcntl.h>_

_int main (void)_

_{_

_int fd\[2\];_

_char buf1\[12\] ="hello world";_

_char buf2\[12\];_

_// assume demo.txt is already created_

_fd\[0\] = open("demo.txt", O\_RDWR);_

_fd\[1\] = open("demo.txt", O\_RDWR);_

_write(fd\[0\], buf1, strlen(buf1));_

_write(1, buf2, read(fd\[1\], buf2, 12));_

_close(fd\[0\]);_

_close(fd\[1\]);_

_return 0;_

_}_

**Output:**

hello world

**Example**: C program to illustrate create system call.

_#include <stdio.h>_

_#include <sys/types.h> /\* defines types used by sys/stat.h \*/_

_#include <sys/stat.h> /\* defines S\_IREAD & S\_IWRITE \*/_

_int main()_

_{_

_int fd;_

_//create data.txt, S\_IREAD is used for read permission bit for the owner_

_//of the file, S\_IWRITE is used for write permission bit for the owner of_

_//the file._

_fd = creat("data.txt", S\_IREAD | S\_IWRITE);_

_if (fd == -1)//check for error in creation_

_printf("Error in opening data.txt\\n");_

_else_

_{_

_printf("data.txt opened for read/write access\\n");_

_printf("data.txt is currently empty\\n");_

_}_

_close(fd);//close the file_

_exit (0);_

_}_

**Example**: C program to illustrate lseek system call.

_#include <stdio.h>_

_#include <fcntl.h>_

_int main()_

_{_

_int fd;_

_long position;_

_//open data.txt file in read-only mode_

_fd = open("data.txt", O\_RDONLY);_

_if ( fd != -1)_

_{_

_position = lseek(fd, 0L, 2); /\* seek 0 bytes from end-of-file \*/_

_if (position != -1)_

_printf("The length of data.txt is %ld bytes.\\n", position);_

_else_

_perror("lseek error");_

_}_

_else_

_printf("can't open data.txt\\n");_

_close(fd);_

_}_

## **Reading Summary:**

In this reading, you have learned the following:

-   The usage of various system calls related to file management like open(), close(), read(), write(),creat(), and lseek




## **Reading Objective:**

In this reading, you will be able to understand and use advanced system administration-related commands like su, passwd, adduser, userdel, groupadd, and groupdel.

## **Main Reading Section:**

**su** (also known as a substitute or switch user): you can accomplish commands with the privileges of another user by default root. During a current login session, su command is the easiest way to switch to the administrative account.

When a user runs the su command, they are prompted for the password of the user account they are trying to switch to. Once the password is entered, the user is logged in as the target user and can execute commands with that user's privileges.

**Syntax**: su \[OPTIONS\] \[USER \[ARGUMENT...\]\]

**Example:** Switching to root user.

![](Essential%20Reading%20System%20Administration%20Advance%20Commands%20%20Coursera/BL4MSgzsRlOG_4GMOYsKKA_897d144ba3b34200b0987a71f74729a1_image.png)

The **passwd** command changes passwords for user accounts. A normal user may only change the password for their own account, whereas the superuser can change the password for any account.

**Syntax**: passwd \[options\] \[username\]

**Example:** Changing password for user1.

![](Essential%20Reading%20System%20Administration%20Advance%20Commands%20%20Coursera/nSU-h1G2QM2RrXA9SdfBmg_20c01fdadb5442ca8fddea3848a31ca1_image.png)

The **adduser** command in Linux creates a new user or group. By applying various options, adduser allows customizing settings in the user provisioning process. The command is a high-level interface for useradd and features interactive prompts when creating new accounts.

**Syntax**: sudo adduser <options> <username>

![](Essential%20Reading%20System%20Administration%20Advance%20Commands%20%20Coursera/HlUzh358T1WgFR3vB83YpQ_6f0af4c76c2c488687df41bbfce5e8a1_image.png)

**userdel** command in the Linux system is used to delete a user account and related files. This command basically modifies the system account files, deleting all the entries that refer to the given username.

**Syntax**: userdel \[options\] \[username\]

![](Essential%20Reading%20System%20Administration%20Advance%20Commands%20%20Coursera/XygY6O1MTwK3WurThkQ6fg_2ed54c0a3fb8464799ddb5fd884924a1_image.png)

**groupadd** command is used to create a new group. Using groups, we can group together a number of users and set privileges and permissions for the entire group.

**Syntax**: groupadd \[option\] group\_name

![](Essential%20Reading%20System%20Administration%20Advance%20Commands%20%20Coursera/Xs3eZokwTPqmJY8UeDGWjQ_d48b777bd800445badf47c397e806fa1_image.png)

**groupdel** command is used to delete an existing group. It will delete all entries that refer to the group and modify the system account files. It is handled by superuser or root user.

**Syntax**: groupdel \[options\] \[GROUP\]

![](Essential%20Reading%20System%20Administration%20Advance%20Commands%20%20Coursera/9lgvWF6aR-eqwaU2gTpbZw_e83523eb1c54476ca2e515902f5218a1_image.png)

## **Reading Summary:**

In this reading, you have learned the following:

-   The usage of various system administration commands





The solutions for the practice lab, along with the HTML file in module 10, can be accessed through the resource tab of the course. Please click on the below link, which will redirect you to the corresponding folder.

[https://www.coursera.org/learn/command-line-interface-and-scripting/resources/ZJOxW](https://www.coursera.org/learn/command-line-interface-and-scripting/resources/ZJOxW)




Q.1.Ram wants access to one of his nested folders straight from the home folder. Can you support him with the syntax of the suitable commands and options? Also, describe any other three options that can be applied with the same command. **\[5 Marks\]**

Q.2.Explain the numeric and symbolic representations of file permissions with the 'chmod' command and provide practical examples of how these representations are used to modify permissions. **\[5 Marks\]**

Q.3.Discuss four differences between the file systems ext4 and Btrfs and state a use-case of each file system.**\[5 Marks\]**

Q.4.Discuss the commands to identify the hard disk device attached recently and partition the same **\[5 Marks\]**

Q.5.While working on a script named 'script.sh' in the vi editor realised that you have used the variable name 'counter' throughout the script, instead of 'iteration.' Explain how you would use vi commands to search for all occurrences of 'counter,' replace them with 'iteration,' and ensure that you review and confirm each replacement individually. Provide specific examples of vi commands used for search and replace in this scenario. **\[5 Marks\]**

Q.6.How does the seamless data flow between commands via pipelines enhance efficient data processing? Demonstrate using pipelines to retrieve error lines, extract specific fields, count unique field occurrences, and sort them to identify the most frequent error types or timestamps using a sample log file containing ten lines of data.

**\[5 Marks\]**

Q.7.Find the output of the following scripts and provide justification.

**a. \[2 marks\]**

#! /bin/bash

n=10

m=5

echo “The value of n = $n”

echo ‘The value of m = $m’

**b. \[2 marks\]**

#! /bin/bash

x=5; y=6;

term=\`expr $x - $y\`

echo $term

if \[ $term -gt 0 \]

then

echo "x greater than y"

echo $?

else

echo "y greater than x"

echo $?

fi

**c. \[1 mark\]**

#! /bin/bash

x=10

y=5

str="your best Teacher is your last mistake"

echo ${str:x:y}

Q.8.Write a shell script to perform the following:

·Accept two filenames from command line

·Display an error message in case of insufficient arguments.

·If both the files exist then print the message “both files exists”

·If only one file exists, print the name of the file which does not exist with the message “does not exist”

·In case both the files do not exist then display a message “Files does not exist”. **\[5 Marks\]**

Q.9.Write a C program that implements the following using system calls:

·Parent process creates a child process

·The child process prints its own ID

·The child process prints its parent ID (PID).

·The parent process prints multiples of 5 till 50

·The parent will terminate only after the child has terminated **\[5 Marks\]**

Q.10.Write a shell script to validate password strength. Here are a few assumptions for the password string.

·Length– minimum of 8 characters.

·Contain both alphabet and number.

·Include both the small and capital case letters.

·If the password doesn’t comply to any of the above conditions, then the script should report it as a “Weak Password” **\[5 Marks\]**



Q.1.How does the 'touch' command contribute to file and timestamp management, and explain any two options that enhance its functionality? **\[5 Marks\]**

Q.2.Assume you must archive a project for future reference and delete it from the original location. Describe the Linux commands you would use to copy and verify the successful copy while moving the project directory and its contents.

**\[5 Marks\]**

Q.3.Explain any of the five components of an inode. **\[5 Marks\]**

Q.4.Discuss any five options available with 'df' to display disk space statistics and analyze how they contribute to monitoring storage utilization on a system. **\[5 Marks\]**

Q.5.What are the different modes in vi, and explain how users transit between these modes. Also, discuss essential commands for moving the cursor, entering text, and making basic edits. **\[5 Marks\]**

Q.6.Explain how 'wc' is used for word counting, 'sort' for arranging lines in a specified order, and 'grep' for pattern matching. Also, explain how to analyze a log file to count occurrences of specific error messages and sort them based on frequency. **\[5 Marks\]**

Q.7.Write a program using system calls to open a file in read only mode, read line by line and display each line as it is read along with printing the line number. Close the file when end of file is reached.\[5 Marks\]

Q.8.Write a shell script to perform the following:

i.Obtain a string of text from the command line and store in STR1.

ii.Obtain a single character from command line and store it SEARCHKEY.

iii.Count the number of times the SEARCHKEY will repeat in STR1

iv.Write that count to a file named File.txt

v.Display the contents of FILE.txt

For example: contents of STR1 is“An apple a day”

And SEARCHKEY is ‘a’ then, FILE.txt contents should be 4 **\[5 Marks\]**

Q.9.Write a program to create an orphan process. Use kill system call to send SIGKILL signal to the parent process from the child process. What is the main purpose of using kill system call here? **\[5 Marks\]**

Q.10.What is the output of the following program? Justify your answer.

#include <stdio.h>

#include <unistd.h>

int main()

{

if (fork() || fork())

fork();

printf("1 ");

return 0;

} **\[5 Marks\]**
