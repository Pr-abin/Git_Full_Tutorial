# *Git restore, rm, add and mv Concept, use case and command*



1. add  \[Add file on staging]
   		Adds file changes from the working directory to the staging area (index) so they can be committed.
   				Already explained.
   ---
2. mv \[Move and Rename files]
   			Move or rename files
   		git mv *old\_file\_name.txt new\_file\_name.txt* 
   
   ---
3. rm \[Remove files from working tree and index]
   	# Deletes files from disk and from Git tracking.

   	git rm *file\_name.ext   **{ext =file extension}***
   	git rm --cached *file\_name.ext*
   	git rm -rf  # To remove the directory
   
   ---
4. restore \[Restore Working Tree Files]
   		git restore *file\_name.ext*     # To restore the files
   		git restore --staged *file\_name.ext #* To restore unstaged files
   		git restore --source=HEAD --staged --worktree *file\_name.ext   #* To restore staged and unstaged files
   
   ---







