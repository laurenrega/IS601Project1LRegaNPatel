# GitFlow WorkFlow
## What is the GitFlow WorkFlow?

![GitFlow](/GitFlow.svg)

- The Gitflow Workflow was created by Vincent Driessen.  It is a branching model used to manage Git projects that have multiple releases or a scheduled release cycle. The Gitflow Workflow encourages the use of various branches with specific functions, and it provides a framework for when to merge the branches. This provides the ability to maintain organization throughout the entirety of the project, and clarifies each release. Again, each branch in a Gitflow project serves a very specific purpose. The Master branch contains only the actual release information. The parallel Development branch serves as an integration branch for features. Each Feature has its own branch, and is pushed to the Development branch when ready. Feature branches do not directly interact with the Master branch, as it is possible that they may need to be pushed back from the Development branch for edits. Once the Development branch has all features required for a release, the branch is finally merged with the master. There are also Hotfix branches, which serve the purpose of quickly solving release issues. Collaborators will work quickly to resolve these issues to limit release delay. Once the fix is complete, the Hotfix branch is merged to the Master and Development branch. When the release is complete, the Master branch is saved with a version number and the cycle repeats for the next release. The Gitflow Workflow is a great method for collaborative projects. The branch organization allows for clarity and fewer errors. 


**Helpful Links:**
- [GitFlow WorkFlow](https://www.atlassian.com/git/tutorials/comparing-workflows/gitflow-workflow#:~:text=The%20overall%20flow%20of%20Gitflow%20is:%201%20A,branch%20is%20created%20from%20master%20More%20items...)
- [Introducing Gitflow](https://datasift.github.io/gitflow/IntroducingGitFlow.html)
