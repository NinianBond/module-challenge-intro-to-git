## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
Answer:  A version control system for storing or pushing code to the remote repository of github using the program git in the terminal or shell.  Git enables you to create a backup of your code, share it with others, and track changes or debug when necessary. 
2. What is the difference between Git and GitHub?
Answer: Git is the shell program used to track changes locally running on your personal computer.  GitHub is the remote location where we store our code or repositories for collaboration including forking, cloning, pull and merge requests ect.  
3. Why do we create a branch?
Answer:  We create branches to comparmentalize the work we do on a large codebase that will be used by many different people.  
4. What is the purpose of a Pull Request?
Answer:  A pull request precedes the merge of a branch before it is made one with the main or master.  
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
Answer: git checkout main
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
Answer: git fetch will download code from a remote repositories url to your local computer just like git clone. git merge will merge different peoples work together with yours. and git pull combines the work of git fetch and git merge.
7. What is a merge conflict?
Answer: A merge conflict occurs when two people make different edits to the same line in a specific file.  Or when one person is editing a file another person has deleted. 
8. How do you resolve a merge conflict?
Answer: There is a conflict editor on GitHub which allows you to reconcile competing line edits in the event of a merge conflict.  In the event of the deleted file somone or you happened to be also editing you must decide whether to keep the deleted file by using git status and git add from the command line.  
