# Task 7: Complete Interactive Rebase :
## 1. After modifying the commits, save and close the editor.
## 2. Resolve any conflicts if prompted, then continue the rebase:
git rebase --continue
```bash
+ The command git rebase --continue is used to continue a rebase process after resolving any conflicts during an interactive rebase or a regular rebase.
```


# **Task 6: Use Interactive Rebase to Modify Commit History :**
# **1. View the last few commits :**

git log --oneline
```bash
Ans:
1. The command ```git log --oneline``` is used to display a simplified, one-line summary of the commit history in your Git repository.
```
# **2. Start an interactive rebase for the last 3 commits :**
git rebase -i HEAD~3
```bash
1. The command git rebase -i HEAD~3 is used to interactively rebase the last 3 commits in your current branch.

2 .Interactive Rebase : The -i flag stands for "interactive," meaning you can choose to modify commits, reorder them, squash them, or drop them during the rebase process.

3. HEAD~3: This specifies the starting point for the rebase. HEAD~3 means "the commit three steps before the current HEAD," i.e., the last three commits you made in your current branch.
```
# **3. Modify the commits by changing pick to one of the following**:
+ ```squash``` (combine commits)

+ ```reword``` (edit commit message)

+ ```edit```(edit commit content)

+ ```drop``` (remove commit)
# **4. Example of squashing two commits :**
+ Change the second commit from pick to squash and save.

+ Git will combine the commit messages for the squashed commit.
