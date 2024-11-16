# Part 2: Working with Repositories
## Task 7: Branching and Merging
### 1.Create a new branch for a feature:
git branch feature-login
git checkout feature-login

ANS:
-git branch will make a new branch named feature-login 
-git checkout  will change the branch to feature-login 
-or we can use git checkout -b feature-login that will make a branch and change  it in one step   

### 2.Add a new file and commit changes:
echo "Login Page" > login.html
git add login.html
git commit -m "Added login page"

ANS:
-it will make a file named login page
-then that file is added and that file go to the staging area
-then that file funally commited to the repo

### 3.Merge the feature branch into main:
git checkout main
git merge feature-login

ANS
- it will chnage branch to main
-now we are in main branch now we can write ths code to meage feature-login to main branch

