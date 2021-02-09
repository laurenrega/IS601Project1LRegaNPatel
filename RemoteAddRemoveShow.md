# Remote Add/ Remove/ Show
## What are the Git Remote Add, Remove, and Show Commands?

- Remote repositories allow programmers to easily collaborate on a project. The git remote commands such as add, remove, and show, allow the user to access and edit the remote repository connections from their computer. Git remote add creates a new connection to the desired remote repository. Git remote rm (remove) will remove the connection to the targeted remote repository. The command git remote (show) will show the user their current connections to remote repositories. Programmers will use the git remote commands to push and pull their commits to and from remote repositories.

## Example:
- To show the remote repository connections I currently have, I type *git remote* in the command line

![Remote1](/Remote1.png)

-	I want to add a new connection, so I type *git remote add <name> <url>*

![Remote2](/Remote2.png)

- I then typed *git remote* again to make sure my connection was added
- Nevermind! I no longer want the second connection, so I type *git remote rm <name>*; and then I do another *git remote* to verify my changes. 

![Remote3](/Remote3.png)

- It worked! It is easy to add, view, and remove remote repository connections!

**Helpful Information:**
- [Git Remote](https://www.atlassian.com/git/tutorials/syncing)
