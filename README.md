# DevOps-courses
## Git workflow

1. Create a branch with the name of the task.
2. Develop the code and create a pull request with changes to the master branch
3. After the merge, build and deploy will automatically start

# The partner in his project will use Gitflow Workflow.
1. First, for convenience, you can install the Git-flow extension $ git flow init
2. GitFlow is a set of Git commands that allows you to perform many operations on a repository with just one command.
3. Everything in the master branch is available for deployment and is stable.
4. To work on something new, create a fork from the master and give it a descriptive name (new_feature).
5. Also, you can create branches from an existing feature branch.
6. Make a local commit to this branch and regularly push your work to the branch of the same name on the server.
7. When you need feedback or help, or you think a branch is ready to be merged, open a pull request.
8. After someone else has reviewed and validated the feature, you can combine it with the master.
9. After merging and submitting to the master, your function is ready to be deployed.
