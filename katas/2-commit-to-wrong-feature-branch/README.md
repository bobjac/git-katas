# Commit to Incorrect Feature Branch

This kata runs through the process of recovering from commiting to the incorrect feature branch. When working on multiple features in parallel, it is common to have multiple feature branches that will house your commits. There will be times when you accidentally commit to the incorrect feature branch. This kata walks through the process to moving a commit from one feature branch to another.

## Instruction Steps

To replicate commiting to the incorrect feature branch, you will need to set up your branches and commit log. 
You can do this by executing the following setup instructions:

### Setup Instructions
1. Create a new feature branch off the current commit, but keep the HEAD pointed to the main branch.
2. Create a second feature branch off the current commit, but keep the HEAD pointed to the main branch.
3. Checkout the first feature branch.
4. Create a new file called my-update.txt.  Add some random text to the file and save it.
3. Add the new file to git so that it is tracked.
4. Commit the change with a commit message.

### Scenario / Resolution
At this point, if you have set everything up correctly, you have committed your changes directly to the first feature branch when you wanted to commit to the second feature branch. As a kata exercise, you will now need to resolve this.

### Kata Instructions
1. Don't panic.  There are ways to resolve this.  
2. Visit public resources or use git help to move the latest commit to another branch.
3. Remember to return the first feature branch to the proper state (the commit prior to your change).