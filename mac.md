## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch? 
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

1. Git is an Open Source Distributed Version Control System.
2. Git is a content tracker, while GitHub is a cloud-based git hosting service.
3. To create an independent line of development, so our work is isolated from other team members.
4. To update the current local branch and update remote-tracking branches for all other branches.
5. You can use git switch - command to undo changes and return to previous branch, or use git swith -c <new-branch-name> to create new branch.
6. `git fetch` downloads commits, files, and refs from a remote repository into your local repo. `git merge` combines multiple sequences of commits into one unified history. `git pull` will fetch and download content from a remote repository and immediately update the local repository to match that content. Fetch will download, Merge will combine, and pull will take from remote repo and update to local repo.
7. A merge conflict is when competing changes are made to the same line of file.
8. You can resolve it by opening it and making neccessary changes. Once edited use git add a command to stage the new merged content. Lastly, create a new commit with git commit command.