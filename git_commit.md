# What is ***Commit*** in git**?**

###### A commit in Git is a permanent snapshot of staged changes saved in the repository history.



##### Each Commit includes:

* ###### Each commit includes:
* ###### The changes made
* ###### Author name and email
* ###### Date and time
* ###### A unique commit hash
* ###### A commit message



1. ### Command for Commit 

&nbsp;		git commit -m " write your information on what you fixed with this commit"        ## message is necessary

&nbsp;		git commit -a -m "your work info" 			(commit for all staged files of this repository)

&nbsp;		

&nbsp;		git add file1 file2   				Commit for specific files 

&nbsp;		git commit -m "write your info"



### 2\. Amend (modify last commit)

* &nbsp;	Change last commit message:

&nbsp;		git commit -amend -m "Write new message of last commit"

&nbsp;		git commit -amend

&nbsp;		git add .

&nbsp;		git commit -amend



### 3\. Commit with author/ date override

&nbsp;		git commit --author="Name <email@example.com>" -m "Message"	\[commit with author]

&nbsp;		git commit --date="2025-01-01 10:00:00" -m "Message"     	\[commit with date]



### 4\. Commit without hooks or verification		

&nbsp;		git commit --no-verify -m "Message"  





#### &nbsp;	1. What are Hooks in git?

#### &nbsp;		Git hooks are scripts that run automatically at specific stages of the Git workflow to enforce rules and automate tasks.





### 5\. Fixup commits

&nbsp;	A fixup commit is a special commit used to correct or adjust a previous commit without keeping a separate commit message.



&nbsp;	

&nbsp;	command for Fixup commits 

###### &nbsp;		git commit --fixup commit\_hash





### 6\. Squash commits

&nbsp;	Squashing combines multiple commits into a single commit.



&nbsp;		Command for Squash commits 

###### &nbsp;		 git rebase -i --autosquash



#### 7\. For View Commit Information 

&nbsp;		git log				To view commit information.

&nbsp;		git log --oneline 		The summary of the work history.

&nbsp;		git show 			To view Detailed information about the work history.



## Undo commit 



1. #### Undo last commit (Keep changes staged)

&nbsp;		

&nbsp;		git reset --soft HEAD-1

&nbsp;		git reset --mixed HEAD-1





#### 2\. Undo last commit (Delete changes)

&nbsp;		git reset --hard Head-1 

&nbsp;		git revert commit\_hash



&nbsp;	



### Git commit commands are used to save, modify, sign, inspect, and undo snapshots of changes in a repository.





























