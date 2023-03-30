## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation)
 are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?
1. Git is a distributed version control system. It tracks any changes made to any computer files generally among programmers.
2. Where git is a version control system letting you manage code history, GitHub is a cloud service that lets you manage Git repositories.
3. We create a branch off the original source code so as to create a snapshot of what the programmer is working on to make it easier to work on any potential bugs in the future from any changes made to the code.
4. Pull requests are made to inform others that you've made changes to your branch so the coding can be discussed and potentially collaberated on.
5. First list the branches with $ git branch -a to see available branches, the use $ git branch *name of desired branch* then use $ git status to make sure all is well
6. 'git fetch' fetches the changes, 'git pull' merges them after fetching them in one command, and git merge essentially is the same as get pull but you must use the fetch command as well as the merge command instead of just using the pull command.
7. A merge conflict happens when you merge branches with competing commits
8. you have to manually edit the conlflicted file to select the changes you want in the final merge
 
