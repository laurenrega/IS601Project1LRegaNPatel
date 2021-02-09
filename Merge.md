# Merge
## What is the Git Merge Command?

- The git merge command is simply a way to combine branches. So, git merge will take the commits from the branch that the user has worked on, and add them to the targeted branch. The source branch will remain as is, and the targeted branch will accept the change. So, if a user creates a branch to add a new feature, the user would merge the feature from the new branch to the master branch once the feature was completed.  After the merge, the master branch would contain the contents of the new feature and the feature branch would remain the same. It is possible to have a merge conflict if both of the branches have updated the same part of the code. In this case, Git will show the user that a conflict exists, and the user will have to resolve. 
