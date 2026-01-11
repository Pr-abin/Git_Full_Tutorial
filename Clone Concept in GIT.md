# ***Clone Concept in GIT***



###### **Cloning in Git is the process of copying an existing repository, including its complete history, from a remote location to a local machine.**



###### **Why git clone is important**

###### 

1. ###### **First step to work on a project**
1. 
**###### &nbsp;	It brings an existing project to your local machine.**

###### 

###### **2. Creates a full backup**

###### 	**Git is distributed; every clone has the complete history.**

###### 

###### **3. Enables collaboration**

###### 	**Multiple developers can clone the same repository independently.**



##### **Command for Clone** 



	**git clone https://github.com/user/project.git (GitHub URL)**     

						**(You can access this link from GitHub link must end with .git)**

	**cd (Name of Directory)**





	**git clone -b branch\_name URL     # clone specific branch**

	**git clone --depth 1 URL          # shallow clone**

	**git clone URL new\_folder\_name    # custom folder name**





# **Fork Concept in Git**

##### **Forking creates a new copy of a repository on a remote platform (GitHub/GitLab) under your account.**



### **Comparison between Clone and Fork**



**| Feature         | Clone          | Fork                   |**

**| --------------- | -------------- | ---------------------- |**

**| Location        | Local machine  | Remote (GitHub/GitLab) |**

**| Ownership       | Original owner | Your account           |**

**| Push permission | Required       | Always                 |**

**| Git command     | Yes            | No                     |**





#### **Shallow Clone**



##### 	**Partial history clone**



###### 		**git clone --depth 1 <repo\_url>**







