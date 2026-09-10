# Bulk Copying

Some of the most common commands we use are those that allow us to copy. In DOS/Windows, try running the commands

__help copy__

__help xcopy__

__help robocopy__

We know how to use copy source destination and the other commands are just a sophisticated version allowing recursive copies of files and directories to be copied.

Go to your home directory and try the command __xcopy .\CLI .\CLI2__

Use the __tree__ command to verify what happened.

Empty directories were ignored and there were no files in any of the backup directories.

We could use some of the switches in xcopy to make life easier. Try the command 

__xcopy .\CLI .\CLI3 /E /I /F __

and use the command __tree__ to ensure it worked.

There is a more modern command called __robocopy__ which is much more appropriate for use over a network on a modern system. Using help, figure out how to create a directory CLI4 with all the subdirectories and files within.

Now clean up the mess; delete the directories you have created.
