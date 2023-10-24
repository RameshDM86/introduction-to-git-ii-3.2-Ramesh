# My Understanding of GIT -3.2-Ramesh #

+ **GitHub authentication** refers to the process of verifying the identity of users and applications accessing GitHub services and repositories. It is essential for maintaining  the security and integrity of code and other resources hosted on GitHub. GitHub offers several methods for authentication, depending on the type of user or application   and the level of access required. Here are some common authentication methods used on GitHub:

## Username and Password Authentication: ## 

*    Users can log in to GitHub using their usernames and passwords. This is the most common method for individual users.
*    You can also generate personal access tokens and use them as an alternative to passwords for authentication. These tokens can be revoked or limited in scope, making them
      more secure for automated tasks.

## Two-Factor Authentication (2FA): ## 

* Users can enable 2FA to add an additional layer of security to their GitHub accounts. This typically involves receiving a one-time code on a mobile device or via an 
  authentication app.


## SSH Key Authentication: ## 

* SSH keys can be added to a user's GitHub account for authentication. This is a secure method often preferred for automated workflows and code deployments.

## Update the Readme file to contain least 15 github commands and what are the usage of them? ## 

 * Initialize a New Git Repository:
         ` git init ` &nbsp; &nbsp; This command initializes a new Git repository in the current directory.

 * Check Status of Your Repository:
           ` git status`   &nbsp; &nbsp; It shows the status of changes in your repository, including untracked, modified, and staged files.

 * Add Changes to Staging Area:
       `git add <file_name> ` &nbsp; &nbsp; Add changes from your working directory to the staging area to prepare for a commit.

*  Commit Changes:
      ` git commit -m "Your commit message" ` &nbsp; &nbsp; Create a new commit with changes from the staging area along with a descriptive message.

* Pull Changes from a Remote Repository:
      ` git pull ` &nbsp; &nbsp; Fetch and merge changes from a remote repository into your local branch.

* Push Changes to a Remote Repository:
      ` git push `  &nbsp; &nbsp;  Push your local commits to a remote repository.

* Create a New Branch:
      ` git branch <branch_name> ` &nbsp;&nbsp; Create a new branch with the specified name.
  
* Delete a Branch
   ` git branch -d <branch_name> ` &nbsp;&nbsp; Delete a Branch   

* Switch to a Branch:
      `git checkout <branch_name> ` &nbsp;&nbsp; Switch to an existing branch.

* Merge a Branch into the Current Branch:
      ` git merge <branch_name> ` &nbsp; &nbsp; Merge changes from another branch into the current branch.

* List Branches:
      ` git branch `  &nbsp;&nbsp;  List all branches in the repository.

* Delete a Branch:
      ` git branch -d <branch_name> ` &nbsp;&nbsp;  Delete a branch if it has been merged into the current branch.

* Fetch Changes from a Remote Repository:
      ` git fetch `  &nbsp;&nbsp; Fetch changes from a remote repository without merging.

* Set your Git username:
      `git config --global user.name "Your Name" ` &nbsp;&nbsp; Configure your Git username.

* Set your Git email:
      ` git config --global user.email "your@email.com" ` &nbsp;&nbsp; Configure your Git email address for commits.


## 4 Github commands that you think you will use the most in the real project and why? Explain it on the readme file ##

 + git status
 + git add main.tf
 + git status
 + git commit -m "adds main.tf" IE
 + git push

* The reason i feel that these commands are mostly use is this creates projects. Without Projectes create there would be no reson for ` Git Pull ` &  ` Git Merge `
