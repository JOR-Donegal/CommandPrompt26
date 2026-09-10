# Making, Deleting and Changing Directories

To keep our files organized, we need to be able to make and delete directories. We also need to be able to change working directory as required. Note that commands in Unix and DOS are similar but not the same. In either operating system, the __tree__ command gives a nice overview of the directory tree structure from the working directory down.

The command __cd__ _directoryname_ changes the working directory.
The command __md__ _subdirectory_ makes a new directory.
The command __rm__ _subdirectory_ removes a sub directory.

## Exercise

1. Go to you home directory.
2. Create a directory called CLI
3. Change your working directory to CLI
4. Create a directory called Backup under the directory CLI
5. Create a directory called Test under the directory CLI
6. Return to your home directory by typing __cd__ on its own. You will often see __cd ~__ used, it has the same effect.
7. Use the __tree__ command to review what you have done.
8. Delete the directory called Test, you may have to navigate to it
9. Check the result of the command __cd ..__