# 15 basic Git command

## Commands----

1) Git Init-<br>
•	The git init command creates a new Git repository.<br>
•	Git init is one way to start a new project with Git.<br>
•	To initialize a repository, Git creates a hidden directory called (.git)
![](images/git_init.JPG)<br>

###############################################################################################################################################################

2) Git Clone-<br>
•	git clone is primarily used to point to an existing repo and make a clone or copy of that repo at in a new directory, at another location.<br>
•	The git clone command copies an existing Git repository.<br>
![](images/git_clone.JPG)<br>

###############################################################################################################################################################

3)	Git Status-<br>
•	The git status command displays the state of the working directory and the staging area.<br>
•	Git staus lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git.<br>
![](images/git_status.JPG)<br>

###############################################################################################################################################################

4) Git add-<br>
•	The git add command adds a change in the working directory to the staging area.<br>
•	Git add tells Git that you want to include updates to a particular file in the next commit. <br>
•	Git add doesn't really affect the repository in any significant way—changes are not actually recorded until you run git commit. <br>
•	Basic way to write the git add command are – a) git add . (where . signifies changes in the multiple files done) b) git add <filename> (If you want to git add particular file ) <br>
![](images/git_add.JPG)<br>

###############################################################################################################################################################

5)	Git branch-<br>
•	A branch in Git is simply a lightweight movable pointer to one of these commits.<br>
•	Git branch can give you the list of branches exists and in which branch you are currently working.<br>
#### redirecting to main branch and by using *git branch* checking the list of branches.<br>
![](images/git_branch1.JPG)<br>
#### creating new branch<br>
![](images/git_branch2.JPG)<br>

###############################################################################################################################################################

6)	Git checkout-<br>
•	The git checkout command lets you navigate between the branches created by git branch .<br>
•	Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that         branch.<br>
![](images/git_checkout.JPG)<br>

###############################################################################################################################################################

7)	Git pull-<br>
•	The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content.<br>
![](images/git_pull.JPG)<br>

###############################################################################################################################################################

8)	Git revert-<br>
•	The git revert command is a forward-moving undo operation that offers a safe method of undoing changes. <br>
•	Instead of deleting or orphaning commits in the commit history, a revert will create a new commit that inverses the changes specified. <br>
•	Git revert is a safer alternative to git reset in regards to losing work.<br>
![](images/git_revert.JPG)<br>

###############################################################################################################################################################

9)	Git config –global-<br>
•	To set your Git username<br>
•	Git username does not need to be the same as your version control username, such as the one you use on GitHub.<br>
![](images/git_username.JPG)<br>

###############################################################################################################################################################

10)	Git log-<br>
•	Git log is a utility tool to review and read a history of everything that happens to a repository.<br>
•	Multiple options can be used with a git log to make history more specific.<br>
•	Generally, the git log is a record of commits.<br>
![](images/git_log.JPG)<br>

###############################################################################################################################################################

## Stash change<br>

11)	Git stash-<br>
•	Git stash is a built-in command with the distributed Version control tool in Git that locally stores all the most recent changes in a workspace and resets the state   of the workspace to the prior commit state. <br>
•	A user can retrieve all files put into the stash with the git stash pop and git stash apply commands.<br>
![](images/git_stash.JPG)<br>

###############################################################################################################################################################

12)	Git push-<br>
•	The git push command is used to upload local repository content to a remote repository.<br>
•	Git Push Origin pushes all the branches to the main branch.<br>
![](images/git_push.JPG)<br>

###############################################################################################################################################################

13)	Git fetch-<br>
•	Git fetch is a primary command used to download contents from a remote repository.<br>
•	Git fetch is the command that tells the local repository that there are changes available in the remote repository without bringing the changes into the local         repository. <br>
![](images/git_fetch.JPG)<br>

###############################################################################################################################################################

14)	Git Rebase-<br>
•	Git Rebase is the process of moving or combining a sequence of commits to a new base commit.<br>
•	Git merge is a command that allows you to merge branches from Git whereas Git rebase is a command that allows developers to integrate changes from one branch to       another.<br>
![](images/git_rebase.JPG)<br>

###############################################################################################################################################################

15)	Git show-<br>
• Git show is a command line utility that is used to view expanded details on Git objects such as blobs, trees, tags, and commits.<br>
• Git show command is similar to git log in terms of output. Git show also presents you the output in the same format as we studied in the git log tutorial. A slight     difference is that the git show command shows you two things: The commit to which HEAD is pointing.<br>
![](images/git_show.JPG)<br>
