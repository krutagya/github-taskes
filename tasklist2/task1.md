# **Task 1: Install and Configure Git**
## **1.Install Git from git-scm.com.**
```bash
ANS:
It create a git directory and used to initalize a new git repository in your project
```
## **2.Configure your global Git settings:**
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

ANS:
```bash
The git config command is used to configure settings in Git. It allows you to set configuration options, such as your name, email, preferred editor.
If we want to change then we can target that keyword and name it and write it in double quotes.

There are three ways to config first is global level,system level and local level
1.--global level :- In which changes are done in user stystem and store in user's home directory 
2.--system level :-In which changes are done in whole system and affect all user which will use in that   system
3. --local level:-In which it Applies to a specific repository and is stored in the repository.
```

## **3.Verify the configuration:**
git config --list

ANS:
```bash
The git config --list command is used to display all the configuration settings currently applied in Git. It shows the combined configuration from the system, global, and local levels. If there are overlapping settings, the more specific level overrides the others (local > global > system).
```