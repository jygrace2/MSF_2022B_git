# Git Lesson

This lesson covers the basics of using git for version control.

This lesson is for the first day of the 2022B MSF (MolSSI Software Fellow) Bootcamp.

To make a commit of your files:
1. Make changes to your project that you would like to keep.
2. Add files you want to be in the commit to the staging area using "git add FILENAME"
3. Create a checkpoint (or commit) using the "git commit" command. "git commit -m "MESSAGE ABOUT WHAT YOU DID""
 
### Adding features
Features should be developed on branches.
To create and switch to a branch, use the command

`git switch -c new_branch_name`

To switch to an existing branch, use

`git switch branch_name`