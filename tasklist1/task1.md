# 1.Configure Git with your username and email
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"

ANS:- 
The git config command is used to configure settings in Git. It allows you to set configuration options, such as your name, email, preferred editor.
If we want to change then we can target that keyword and name it and write it in double quotes.

There are three ways to config first is global level,system level and local level
--global level :- In which changes are done in user stystem and store in user's home directory 
--system level :-In which changes are done in whole system and affect all user which will use in that   system
--local level:-In which it Applies to a specific repository and is stored in the repository.

# 2.View your Git configuration
git config --list

ANS:-The git config --list command is used to display all the configuration settings currently applied in Git. It shows the combined configuration from the system, global, and local levels. If there are overlapping settings, the more specific level overrides the others (local > global > system).

