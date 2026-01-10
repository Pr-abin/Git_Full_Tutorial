# The Concept of fetch, pull, push, remote and checkout



1. The concept of fetch
   	# git fetch downloads updates (commits, branches, tags) from a remote repository without changing your working code.

   	# git fetch origin		# Download updates from remote 'origin' only
   	# git fetch --all		# Fetch updates from all remotes
   	# git fetch origin main		# Fetch updates for a specific branch
   	# git fetch --prune		# Remove deleted remote branches locally 
   	
   ---
2. The concept of remote
   	# git remote manages connections to remote repositories (like GitHub).

   Commands 
   	# git remote -v			# Show remote names with URLs (fetch \& push)
   	# git remote add *name\_of\_repo* *url\_of \_remote\_repository*	# Add a new remote repository named origin
   	# git remote remove origin		# Remove a remote repository
   	# git remote *rename old\_repo\_name* new\_repo\_name	# Rename a remote repository
   
   ---
3. The concept of pull
   	# git pull downloads updates and immediately integrates them into the current branch.

   Command for pull

   	# git pull		# Fetch and merge updates into current branch
   	# git pull origin main	# Fetch and merge main branch from origin branch
   	# git pull --rebase	# Fetch and reapply commits instead of merging
   	# git pull origin *name\_of\_branch*	# Pull a specific branch
   ---
4. 
5. The concept of push
   	# git push uploads your local commits to a remote repository.

   Commands for push
   	# git push			# Push current branch to its upstream branch
   	# git push origin main		# Push local main branch to origin
   	# git push -u origin feature	# Push branch and set upstream (first time push)	
   	# git push --all		# Push all local branches
   	# git push --tags		# Push all tags to remote
   	# git push origin --delete feature	# Delete remote branch
   ---
6. The concept of checkout
   	git checkout is used to　switch branches and restore files from commits
   	
   Command for Checkout
   	# git checkout main		# Switch to main branch
   	# git checkout -b feature		# Create and switch to new branch
   	# git checkout origin/main		# Checkout remote branch in detached HEAD state
   	# git checkout -- file.txt		# Discard changes in a file (restore from last commit)
   	# git checkout commit\_hash		# Move to a specific commit (detached HEAD)
   	# git checkout -b feature origin/feature		# Create local branch tracking remote branch
   ---
