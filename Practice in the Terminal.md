# Practice in the Terminal

### introduction
CLI, or command-line interface, is a type of user interface that allows users to interact with a computer program or operating system by typing commands into a terminal rather than using a graphical user interface. Linux is a free and open-source operating system based on Unix, known for its power and flexibility. Mastering the command-line interface is an essential skill for developers, as it allows them to perform a wide range of tasks more efficiently and effectively than using a graphical user interface.

### The Command Line
The CLI is a text-based interface where users can interact with the system by typing commands into a terminal. It's different from the graphical user interface (GUI) and can be used in conjunction with it. the shell is the part of the operating system that defines how the terminal behaves. The most common shell in Linux is called bash.to check which shell is being used.

```
echo $SHELL
```

### Basic Navigation!
The 'pwd' command shows the current directory, and the 'ls' command lists the files and directories in the current location. 'ls' has options and arguments to do more things, and it can also list the contents of other directories. Paths are a means to get to a file or directory on the system, and there are two types of paths: absolute and relative. Absolute paths start with a forward slash and specify a location in relation to the root directory, while relative paths do not start with a slash and specify a location in relation to the current location.

### More About Files!
Linux sees everything as a file, including directories, text files, keyboards, and monitors. Linux is an extensionless system, meaning that the system ignores file extensions and looks inside the file to determine the file type.Linux is case sensitive, and files and directories with the same name but different cases are considered as separate. It also deal with spaces in names, using quotes or escape characters. The text also explains that files and directories beginning with a dot (.) are hidden in Linux.

### Manual Pages:
The Linux command line has a lot of power and opportunities, but it can be hard to remember everything. The manual pages are a great resource that explains every command available on your system, including how to run them and what command line arguments they accept. You can invoke the manual pages with the `man` command. You can also search within the manual pages using the "man -k" command and search within a particular page by pressing "/" followed by the search term. To be proficient in Linux, it's important to know which command line options to use to modify the behavior of commands to suit your needs. There are both long hand and short hand versions of these options. Long hand options begin with two dashes and short hand options begin with a single dash.

### File Manipulation!

 - Creating a directory using the "mkdir" command
 - Removing a directory using the "rmdir" command
 - Creating a blank file using the "touch" command
 - Copying a file or directory using the "cp" command

### Refrance [this](https://ryanstutorials.net/linuxtutorial/cheatsheet.php) cheat cheet 
