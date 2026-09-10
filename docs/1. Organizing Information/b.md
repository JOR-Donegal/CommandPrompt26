# Directories and File Structures

Directories would be hard to use if you didn't know which one you were working in!! The directory we are currently in is called the _working directory_ or sometime the _current directory_. We have previously seen how to tell what directory we are in. Now we know where we are the next requirement is to see what files are there.

I do not know what the path will be to your exercises, I'll let you figure that out.

In a DOS command window, type _cd IaC\Week1_ to change your working directory.

__dir__ to get a basic directory listing. In the third column, you may see the text _<DIR>_. Any such entry refers to a sub directory which may contain other files and directories. A directory under another directory is referred to as a sub directory.

__dir /p__ to get a paginated directory, useful when there are very many files

__dir /a__ to show hidden files

__dir /w__ to show files in a wide format

__dir /?__ to get a list of all options

Depending on your OS and how you are viewing it, some of the directory listing shows file names in various colors.

__(.)__ means the current directory, so typing __cd .__ means stay where you are.

__(..)__ means the parent of the current directory, so typing __cd ..__ will take you one directory up the hierarchy. These become very important later!!

For completeness, I should comment that this overview is simplified. Files may be multi-dimensional; they may have other streams apart from the one holding the data. Do an Internet search on _NTFS streams_ to see what I mean. The Apple file system has similar multi-stream support.