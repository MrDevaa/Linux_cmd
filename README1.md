## Browsing directories with the Linux terminal
Learning Objectives
After finishing this reading, you will be able to:

Describe what a Linux terminal is used for
Use the pwd and ls commands to browse directories in your Linux file system
The Linux terminal

You can interact with the Linux shell by entering commands into the Linux terminal, which is also commonly referred to as the command line or the command prompt.

In this case, the present working directory is /home/project, as indicated by the blue text. The dollar sign $ following it is called the command prompt.

Recall that a terminal window is a simple user interface that allows you to run any commands that you would like, simply by typing the command on your keyboard and hitting Enter. Many commands will respond by returning some sort of output, which by default appears as text in your terminal window.

Let's see how this works using a couple of the most common Linux commands, the pwd and ls commands:

Here we've entered the pwd command, which prints the path name for our present working directory on the next line. You can see that the command prints what we expected, which is the path to the present working directory, /home/project. Notice also that the command prompt shows up again on the following line, awaiting your next command.

Great! Now, how do you see what's inside your present working directory?

You can use the ls command to list the contents of the directory you are currently working in. At the moment, the /home/project directory is brand new and doesn't contain anything yet, so entering the ls command will return nothing:

Being a conservative program, ls won't bother with printing a blank line to express that there is nothing to list.

Let's see if we can find a directory that already contains content. You can list the contents of any directory with the ls command by specifying the directory name you'd like to explore.

For example, ls /home lists the contents of the /home directory:

You can see that the directory /home contains two objects, namely project and theia.

Tip: Think of a directory as a folder that contains files and subdirectories. In this case, project and theia are subdirectories of /home. Subdirectories can contain additional files and subdirectories. You'll learn more about exploring subdirectories in later labs.

Notice the naming convention for a directory's path: /home/project indicates that the project directory is a subdirectory of /home. The path for the theia subdirectory would similarly be /home/theia.

Like a tree, your Linux file system has a root directory (/, called "slash") from which your entire Linux file system branches out.

One important subdirectory of your root directory is home. You can see this for yourself by entering ls / to list the contents of /:


Summary
Congratulations! In this reading, you learned that:

You can interact with the Linux shell by entering commands into the Linux terminal
The pwd command prints the path name to the present working directory
The ls command lists the contents of a directory
