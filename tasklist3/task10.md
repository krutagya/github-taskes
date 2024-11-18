# **Task 10: Simulate a Merge Conflict**
## **1.Modify the same line in a file on two branches:**

echo "Main branch content" > conflict.txt
git add conflict.txt
git commit -m "Added conflict.txt in main branch"
```bash
Ans:
1. it will make a file called conflict.txt with the message main branch content
2. it will add that file innto the staging area
3. it will commit and save that file  with the mwssage given in it 
```

## **2.Switch to the other branch and make conflicting changes:**

git checkout feature-branch
echo "Feature branch content" > conflict.txt
git add conflict.txt
git commit -m "Modified conflict.txt in feature-branch"

```bash
Ans:
1. it will shift our branch into the given branch nname
2. it will make a file called conflict.txt with the message feature branch content
3. it will add that file innto the staging area
4.it will commit and save that file  with the mwssage given in it 
```
## **3.Merge feature-branch into main:**

git checkout main
git merge feature-branch
```bash
Ans:
1. it will shift our branch into the given branch name
2. it will merege the data of the fiven branch to the exisiting file you are in
Explanation: Combines the changes from feature-branch into main.
```
## **4.Resolve the conflict by editing the file and choosing the correct version:**

Open conflict.txt and decide which changes to keep.
Stage the resolved file:
git add conflict.txt
Commit the merge:
git commit -m "Resolved conflict in conflict.txt"
```bash
Ans:
1. we have to change in our local
2. it will add that file innto the staging area
3. it will commit and save that file  with the mwssage given in it
```