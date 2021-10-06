# Commit to Main

This kata runs through the process of recovering from commiting directly to the main branch instead of to a dedicated feature branch. It is best practice to prohibit direct commits to the main branch and require all commits to be addred through pull requests from a feature branch. Once a user commits to main, a failure will occure when trying to execute a push.

## Instruction Steps

To replicate commiting to master, you will need to set up your branches and commit log. 
You can do this by executing the following setup instructions:

### Setup Instructions
1. Create a new feature branch off the current commit, but keep the HEAD pointed to the main branch.
2. Create a new file called my-update.txt.  Add some random text to the file and save it.
3. Add the new file to git so that it is tracked.
4. Commit the change with a commit message.

### Scenario / Resolution
At this point, if you have set everything up correctly, you have committed your changes directly to the main branch rather than a feature branch. Committing to feature branches is the preferred practice, and in many cases, branch policies will prohibit pushing commits directly to main. As a kata exercise, you will now need to resolve this.

### Kata Instructions
1. Don't panic.  There are ways to resolve this.  
2. Visit public resources or use git help to move the latest commit to another branch.
3. Remember to return the main branch to the proper state (the commit prior to your change).
