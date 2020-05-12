# Common Bash Commands for Git

Git commands for beginners:

 - Clone or initialize a new repository.
 
 **git init** = initialize a new repository. Write rm -rf .git to delete the entire git repository and undo the changes made by the init command.

**git branch** = check the current branch, if its master and you want to make some changes it's better to make a new branch.
**git checkout -b new_branch_name** = now this is your new branch and you can work on it safely. 

- After making changes: 

**git status** = check all the changes in the working repo

**git add _filename_** = save changes to a specific file

**git add .** = save the changes for all the file in the current branch.

- Update the current brunch in your repository with a commit:

**git commit -m "comment_for_your_commit"** = make all the commit that you want

- Push the changed files in yout Gir repo:

**git push -f** = follow the required steps that the Terminal asks you.

Now you can make a new pull request on you repo, and merge it to the master.

After this step you have to change to the branch master with:

**git checkout master**.

Before make any other changes do not forget to make a new branch, or switch to an existing brunch (git checkout _brunch_name_).

Other changes:

After you switched to a brunch and want to replace some files before the changes do:

**git pull** to download the previous version without any changes or also to download the uptaded master brunch.


**git remote -v** check if you are the owner of that repository


Save user configuration for a repository by reducing the number of times you must type your username and password:

**git config --global credential.helper store --file ~/.my-credentials**

**git push [repository link]**

**username: [type your username]**

**password: [type your password]**


[several days later]


**git push [repository link]**

[credentials are used automatically]

-----------------
