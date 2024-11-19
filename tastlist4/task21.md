# **Task 21: Sync Your Fork with the Original Repository :**
## **1. Add the original repository as a remote source :**

git remote add upstream https://github.com/original-owner/repo.g
```bash
Ans:
1. This sets up a connection to the original repository (referred to as upstream). You would typically use this in a forked repository to pull updates from the original repo.
```
## **2. Fetch changes from the original repository :**
git fetch upstream
```bash
Ans:
1.Fetch Updates :
It downloads all the changes (commits, branches, and tags) from the upstream remote repository.

2.No Merge :
The changes are not applied to your working directory or current branch. They are stored in your local repository under the upstream remote references.
```
## **3. Merge changes from the original repository into your local branch:**
git checkout main
git merge upstream/main
```bash
Ans:
1. The commands git ```checkout main``` and ```git merge upstream/main``` update your local ```main``` branch with the latest changes from the original repository (```upstream```). First, ```git checkout main``` switches to your ```main``` branch. Then, ```git merge upstream/main``` merges the latest updates from ```upstream/main``` (fetched earlier using ```git fetch upstream```) into your branch. This process ensures your local branch is synchronized with the original repository, incorporating any new changes or updates. If there are conflicts, you'll need to resolve them before completing the merge.
```
## **4. Push the changes to your fork :**

git push origin main
```bash
+ The command ```git push origin main``` uploads the changes from your local ```main``` branch to the remote repository named ```origin```.
```
# **Consolidated Summary :**
## 1. **Stashing** : Saving and applying uncommitted changes temporarily.

## 2. **Rewriting History :**  Using git rebase and interactive rebase to modify and clean up commit history.

## 3. **Cherry-Picking :** Selecting specific commits from another branch.

## 4. **Tagging :** Labeling commits for versioning.

## 5. **Working with Remote Repositories :** Managing remotes, pushing, pulling, and fetching changes.

## 6. **Working with Remote Repositories :** Managing remotes, pushing, pulling, and fetching changes.
