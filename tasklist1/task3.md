# Task 3: Create a File and Make Multiple Commits

### 1.Create a new file and add content:
echo "My First Project" > README.md

ANS:
-It will make a new file named as README.md if it not exist 
-it will write a text "MY First Project" in that file
- if file is exist then > this will over writes the message and >> this will apends that message in that existing file




### 2.Stage the file:
git add README.md

ANS:
1.Add changes in a file or files to the staging area also called as index
2.Prepare the files to be included in the next commit.

### 3.Commit the file:
git commit -m "Initial commit: Added README.md"

ANS:
- it is used to create a commit in git which will be saved your staged changes to the repo history
and aslo provide a commit message that are in "  ".

### 4.Make changes to the file:
echo "Added a description" >> README.md

ANS:
-it will make a file and if file is existing than the message will me append or else it will make a file
with message given in it

### 5. Stage and commit the changes:
git add README.md
git commit -m "Updated README with a description"

ANS:
-it will add readme file into the staging area which will be waiting for the commit
- it will commit that file to the repo with the given message in it