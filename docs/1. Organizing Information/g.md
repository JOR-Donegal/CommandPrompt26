# Moving around directories

We will now examine how to move files around using these commands. Before starting, make sure you are in the __\CLI__ directory!

Examine these commands

__copy rubbish.txt rubbish1.txt__

__copy rubbish.txt Backup__

What was the difference in how the command was interpreted?

We can delete files in a directory which is not our working directory, using relative paths, for example

__del Backup/rubbish1.txt__

Now change your working directory to _\CLI\Backup_ and run the commands

__copy ../rubbish.txt .__
__dir__

What happened and why?

In many cases, (.) and (..) are very handy, however they do require you to know what your working directory is. One longer but safer option is to use absolute path names. Try using absolute path names to copy the file __rubbish.txt__ to a backup directory