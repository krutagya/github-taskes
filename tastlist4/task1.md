# **Task 1: Save Changes Temporarily with git stash :**
## **1. Make changes to a file without committing :**
echo "Temporary changes" >> temp-file.txt
```bash
Ans: 
1. It will make the change in file temp-file without committing.
```
## **2. View the status of changes :**
git status
```bash
Ans: 
1. it can show the status of the local repository but in our case it's output will be look like this.
### **Output** :
Changes not staged for commit:
modified:   temp-file.txt
```
## **3. Stash the changes :**
git stash
```bash
Ans: 
1. git stash is a Git command used to temporarily save changes that are not yet ready to be committed. It allows you to "stash" your modifications (both staged and unstaged) so you can work on something else, then come back to your changes later.
```
## **4. View the stashed changes :**

git stash list
```bash
Ans:
1. The command git stash list is used to display a list of all the stashes you have saved. Each stash is shown with a name, such as stash@{0}, stash@{1}, and so on, along with the commit reference and a brief description.
 **Output** :
stash@{0}: WIP on main: 27e5f23 Added temporary changes
```



















































































































































































