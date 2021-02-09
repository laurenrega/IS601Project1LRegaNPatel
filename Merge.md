# Merge
## What is the Git Merge Command?

- The git merge command is simply a way to combine branches. So, git merge will take the commits from the branch that the user has worked on, and add them to the targeted branch. The source branch will remain as is, and the targeted branch will accept the change. So, if a user creates a branch to add a new feature, the user would merge the feature from the new branch to the master branch once the feature was completed.  After the merge, the master branch would contain the contents of the new feature and the feature branch would remain the same. It is possible to have a merge conflict if both of the branches have updated the same part of the code. In this case, Git will show the user that a conflict exists, and the user will have to resolve. 

## Example:
- Merging is super simple in GitHub, once I have completed my feature, I will compare and create pull request
- picture
- I will then ensure that the correct branches are selected, and that the merge is occuring in the direction that I want. (Feature 1 merging -> to master). If there are no conflicts, Github will let me know that I am able to merge
- picture
- Next I will create pull request
- picture
- The user that I am collaborating with will be notified that I would like to merge the commits from Feature 1 to the master
- picture
- The collaborator will review the changes and if all is well, they will select merge pull request
- picture
- •	They will be prompted again to confirm merge
- picture
- Then the merge is complete! Review the master branch to view the changes!
- picture

**Helpful Information:**
- [Git Merge and Rebase Intro](https://www.freecodecamp.org/news/an-introduction-to-git-merge-and-rebase-what-they-are-and-how-to-use-them-131b863785f/)
- [Git Merge](https://www.atlassian.com/git/tutorials/using-branches/git-merge)

