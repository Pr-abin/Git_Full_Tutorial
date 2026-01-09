# What is a version control system?



A Version Control System is a software tool that records, tracks, and manages changes to files over time, especially source code, so that you can review, recover, and collaborate efficiently.



#### Core components



Repository – stores files and their history



1. 		**Repository – stores files and their history** 
2. 		**Commit – a saved snapshot of changes**
3. 		**Branch – parallel line of development**
4. 		**Merge – combines changes**
5. 		**History – record of all modifications**





# What is the basic understanding of git?

Git is a distributed version control system (VCS) used to track changes in source code, facilitate collaboration with others, and efficiently manage different versions of a particular project.



1. Local Version Control     		-→   file\_v1, file\_v2, file\_final  (stores in your local storage)
2. Central Version Control   		-→   Developer → Central Server ← Developer (stores in Central Server)
3. Distributed Version Control



## Local Version Control System



Versions are stored locally on a single computer. Changes are tracked by saving copies or patches.



##### How it works



* File copies: file\_v1, file\_v2, file\_final
* Or simple databases storing file differences



## Central Version Control System



A single central server stores all versions. Developers check out files and commit back to the server.



##### How it works



* Developer → Central Server ← Developer
* stores in the Central Server



## Distributed Version Control System

###### **Each developer has a full copy of the repository, including the complete history.**



##### How it works



**Local Repo ↔ Remote Repo ↔ Other Local Repos**

**Each developer has a full copy of the repository**



#### **Some key differences between (LVCS, CVCS, DVCS)**



**| Feature       | Local VCS | Central VCS | Distributed VCS         |**

**| ------------- | --------- | ----------- | ----------------------- |**

**| Collaboration | No        | Yes         | Yes                     |**

**| Offline work  | Yes       | No          | Yes                     |**

**| Speed         | Fast      | Slow        | Very fast               |**

**| Backup        | Manual    | Server only | Automatic (every clone) |**

**| Failure risk  | High      | Very high   | Very low                |**





#### **The official link for downloading Git**



**links:-** 

[**Official Download Link For Other OS**](https://git-scm.com/install/)

[**Download Link For Windows**](https://git-scm.com/install/windows)





1. **User Creations Command Global User
   		git config --global user.name "Write here your user name" (assign yourself)
   		git config --global user.email "write your email address" (assign yourself)

   		git config --global --list 	\[ To view all Global user]

   		Applies to all repositories for the current system user.**

   ---
2. **User Creations Command System level
   		git config --system user.name "Your Name"   		(Assign Yourself)
   		git config --system user.email "your email address"     (Assign Yourself)

   		Applies to all users on the system (rarely used).**

   ---
3. **User Creations Command Local User**
 		git config user.name "Write here your user name" (Assign yourself)
   		git config user.email "write your email address" (Assign yourself)
   ---

###### 

###### &nbsp;		git config --local --list 	\[ To view all Global users]



###### &nbsp;		Applies only to the current repository.



##### **To show the user name and email**

##### 

##### &nbsp;	git config user.name   \*\* for Know the name of the user 

##### &nbsp;	git config user.email  \*\* for Know the user email



### **To Delete The User \& Email Address**



###### For Global Users 

###### &nbsp;		git config --global --unset user.mane

###### &nbsp;		git config --global --unset user.email

###### 

###### For System Users

###### &nbsp;	     	     git config --system --unset user.name

###### &nbsp;		     git config --system --unset user.email

###### 

###### For local User 

###### &nbsp;		     git config --unset user.name

###### &nbsp;		     git config --unset user.email


Some Linux Commands
===





1. **Directory \& File Navigation  ls, cd, pwd

   	ls              # list files
   	ls -a           # show hidden files (.git)
   	pwd             # current directory
   	cd folder\_name  # change directory
   	cd ..           # move up one directory**

   ---
2. **File \& Directory Management touch, rm, mv, cp

   	mkdir project        # create directory
   	rmdir folder         # remove empty directory
   	rm file.txt          # delete file
   	rm -r folder         # delete folder recursively
   	m -rf .git          # force delete git repo (dangerous)
   	cp a.txt b.txt       # copy file
   	mv old new           # rename / move file
   	touch file.txt       # create empty file**


   ---
3. **File Viewing \& Editing  cat, nano, vi
   	cat file.txt         # view file content
   	less file.txt        # scroll view
   	more file.txt        # basic view
   	nano file.txt        # terminal editor
   	vi file.txt          # advanced editor**


   ---
4. **File Search \& Inspection
   	find . -name file.txt     # search files
   	grep "text" file.txt     # search text
   	grep -r "text" .         # recursive search**

   ---
5. **Disk \& System Info (Occasional)
   	df -h           # disk usage
   	du -sh folder   # folder size
   	whoami          # current user**

   ---
6. **Environment \& History (Very Useful)
   	history            # command history
   	clear              # clear terminal
   	alias gs='git status'
   	export PATH=...**

   ---
7. ###### **Permissions \& Ownership (Sometimes Needed)**
7. 
**###### &nbsp;	chmod 755 file.sh    # change permission**

###### 	**chmod +x script.sh  # make executable**

###### 	**chown user:user f   # change owner (admin)**











