# Task 4: Check Status and Log
### 1.Check the repository’s current status:
git status

ANS:
-The git status command is used to display the current state of the working directory and staging area in a Git repository.
-It will give important information about the file which are modify,added and which are removed 

### 2.View commit history in detail:
git log --oneline 
git log --graph 
git log--decorate

ANS
-in general git log will tell us how many and which which commits are done inshort give all the information about commits
- git log --oneline : it simplifies the output by showing each commits in a single line 
- git log --graph : it will give you a graphical representation about commits where * represents a commit, and the lines (|, /, \,) represent how branches diverged and merged.
- git log --decorate :Git will show extra information about branch names and tags that point to specific commits.