# **Task 2: Apply and Drop Stashed Changes :**
## **1. Apply the most recent stash :**
git stash apply
```bash
Ans:
1. The command git stash apply is used to apply the changes from the most recent stash (or a specific stash) back into your working directory, without removing it from the stash list.
```
## **2. Drop the most recent stash after applying it :**

git stash drop
```bash
Ans: 
1. The command git stash drop is used to remove a specific stash from the stash list. It doesn't apply the changes; it simply deletes the stash you specify.
```
## 3. Alternatively, to apply a specific stash :
git stash apply stash@{1}
```bash
Ans:
1. The command git stash apply stash@{1} is used to apply the changes from the stash with the identifier stash@{1} to your working directory.
```