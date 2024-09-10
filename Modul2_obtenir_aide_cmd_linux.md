Getting Help for Linux Commands
There is huge value in spending time exploring and experimenting with commands, but there are many things you can't figure out just by experimenting. You need to see what's out there, see what's possible, and learn where to look to get answers. Let's take a look at some great ways to get the information you need to help you make progress.

In this reading, you may see links to external sources. You can open them by right-clicking and pressing "Open in new tab."

1. Use the built-in man command
The man command, which stands for "manual", provides the standard way to access help for Unix-like commands from the command prompt. It has been in development since 1971.

You can get a listing of all the commands on your system that have a manual page by entering:

1
man -k .
Copied!
The resulting list includes a brief description of what each command does.

To see the man page for a command, simply enter:

1
man command_name 
Copied!
All man pages are divided into several sections, including:

NAME
The name of the command or feature and a brief description of what it does.

SYNOPSIS
A summary of the command syntax, including any options and arguments that can be used.

DESCRIPTION
A more detailed description of the command, including its function and behavior.

OPTIONS
All the available options and arguments that can be used with the command.

EXAMPLES
Some examples of how to use the command.

SEE ALSO
Related commands and documentation that may be helpful.

You may also see other sections, including: EXIT STATUS, RETURN VALUE, ENVIRONMENT, BUGS, FILES, AUTHOR, REPORTING BUGS, HISTORY, and COPYRIGHT.

2. Install and use the tldr command
Similar to man pages, TLDR Pages is a free and open-source collaborative documentation effort. The goal is to create documentation that is more accessible than the traditional man pages, which tend to be quite verbose.

TLDR Pages, short for "Too Long; Didn't Read" and also known simply as tldr, provide examples for common use cases of various commands. The format of TLDR pages is similar to that of a cheatsheet.

You can install a command-line tool to access TLDR Pages from your terminal. Install it using the following command:

1
npm install -g tldr
Copied!
Once you've installed the tool, you can use the tldr command to easily access the TLDR page of a command.

1
tldr command_name 
Copied!
The tool will display a short, easy-to-understand summary of the command along with some examples of how to use it.

3. Search Stack Overflow
Stack Overflow is a popular community-driven question and answer platform for programmers, developers, and system administrators. It has a vast repository of questions and answers related to various programming languages, tools, and operating systems, including Linux.

To search for information about commands on Stack Overflow, you can use the search bar on the homepage and enter the name of the command you're looking for, along with any specific keywords or parameters. You can also refine your search by adding relevant tags, such as "linux" or "command-line".

Once you've entered your search query, Stack Overflow will display a list of relevant questions and answers that match your query. You can browse through the results to find the information you need, and even post your own question if you can't find an answer to your specific query.

When searching for information about commands on Stack Overflow, it's important to check the date of the answers to ensure that the information is still current and relevant. You should also read through the comments and discussion threads to get a better understanding of the context and any potential issues or limitations related to the command you're researching.

Newest questions on Stack Overflow tagged "Linux": https://stackoverflow.com/questions/tagged/linux

4. Search Stack Exchange
Stack Exchange is a network of question and answer communities, similar to Stack Overflow, but covering a broader range of topics beyond just programming. There are several Stack Exchange communities that specialize in topics related to Linux and open source software, such as Unix & Linux, Ask Ubuntu, and Server Fault.

Visit the relevant community to search for information on Stack Exchange. Like Stack Overflow, you can use the search bar to enter the name of the command you're looking for, along with any keywords or parameters.

Unix and Linux community on Stack Exchange: https://unix.stackexchange.com/

5. Just google it!
Google is a powerful tool that can provide you the answer to almost any question. Learn how to enter the right queries and filter your results, such as by including "Wikipedia", "Stack Overflow", or "Linux" as part of your search. However, use at your own risk. Never blindly trust what you find on the web - there's a lot of noise out there!

6. Use the cheat sheets from this course
Throughout this course, you will encounter "cheat sheets" that condense the information you've learned into easy-to-reference guides. They are great for reviewing the material you've learned and can also help you out with your graded assignments.

7. Refer to Wikipedia's list of Unix commands:
Finally, Wikipedia maintains a list of commands that can be found on Unix operating systems, along with a short description. You can check the page to quickly reference a Unix command: https://en.wikipedia.org/wiki/List_of_Unix_commands

Summary
This reading has provided an overview of how to find more information about Linux commands. As you continue to use commands in this course and beyond, you'll likely find yourself using the same command patterns over and over. Each time you use a command, you'll get a little more comfortable and familiar with it. Your fingers will develop muscle memory until using commands becomes second nature!
