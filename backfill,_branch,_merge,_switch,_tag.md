<<<<<<< HEAD
<<<<<<< HEAD
# The concept of backfill, branch, merge, rebase, and switch
=======
# The concept of backfill, branch, merge, rebase, and switch 
>>>>>>> new_branch
=======
# The concept of backfill, branch, merge, rebase, and switch 
>>>>>>> new_branch



1. The Concept of backfill
<<<<<<< HEAD
<<<<<<< HEAD
   git backfill is used in a partial clone to download missing data (commits, files, objects) that were not downloaded earlier.

   # Command of backfill

    	git backfill      # When you deal with a partial clone

   ---

2. The Concept of branch
   git branch is used to view, create, rename, or delete branches.

   # Command for branch

    	git branch 			# To show the list of Branches
   git branch \*name\\\_of\\\_branch\* 	# To create Branches
   git branch -d \*name\\\_of\\\_branch\*	# To Delete the Branches
   git switch \*name\\\_of\\\_branch\* 	# To switch the Branches

   

   ---

3. The Concept of merge 	\[Combine branches]

   # git merge joins changes from one branch into another.

   # Command for merge

    		git merge name\\\_of\\\_branch

   

   ---

4. The concept of rebase 	\[Move commits onto another base]

   # git rebase reapplies commits from one branch onto another branch, creating a cleaner history.

   # command for rebase

    	git rebase main

   

   ---

5. The concept of switch 	\[Change branches]

   # git switch is a safe and simple way to move between branches.

    	git switch name\\\_of\\\_branch

   

   ---

6. The concept of tag 		\[Mark important points]

   # git tag is used to mark specific commits, usually for releases.

    	git tag first\\\_version.ext      # Create tag
   git tag 		       # List of tag
   git tag -d first\\\_version.ext   # Delete first version of tag

   ---

   

   ## Conclusion

   

   

   ### | Command  | Purpose               | Easy Meaning              |

   ### | -------- | --------------------- | ------------------------- |

   ### | backfill | Download missing data | Complete partial clone    |

   ### | branch   | Manage branches       | Create or delete branches |

   ### | merge    | Combine branches      | Join changes              |

   ### | rebase   | Reapply commits       | Clean history             |

   ### | switch   | Change branches       | Move between branches     |

   ### | tag      | Mark versions         | Label important commits   |
=======
=======
>>>>>>> new_branch
   	git backfill is used in a partial clone to download missing data (commits, files, objects) that were not downloaded earlier.
   		
   	# Command of backfill
   		git backfill      # When you deal with a partial clone
   ---
2. The Concept of branch 
   	git branch is used to view, create, rename, or delete branches.

   	# Command for branch 
   		git branch 			# To show the list of Branches
   		git branch *name\_of\_branch* 	# To create Branches 
   		git branch -d *name\_of\_branch*	# To Delete the Branches
   		git switch *name\_of\_branch* 	# To switch the Branches
   
   ---
3. The Concept of merge 	\[Combine branches]
   	# git merge joins changes from one branch into another.

   	# Command for merge
   			git merge name\_of\_branch
   
   ---
4. The concept of rebase 	\[Move commits onto another base]
   	# git rebase reapplies commits from one branch onto another branch, creating a cleaner history.
   	
   	# command for rebase
   		git rebase main
   
   ---
5. The concept of switch 	\[Change branches]
   	# git switch is a safe and simple way to move between branches.
   		git switch name\_of\_branch
   
   ---
6. The concept of tag 		\[Mark important points]
   	# git tag is used to mark specific commits, usually for releases.
   		git tag first\_version.ext      # Create tag
   		git tag 		       # List of tag
   		git tag -d first\_version.ext   # Delete first version of tag
   ---



## Conclusion 





### | Command  | Purpose               | Easy Meaning              |

### | -------- | --------------------- | ------------------------- |

### | backfill | Download missing data | Complete partial clone    |

### | branch   | Manage branches       | Create or delete branches |

### | merge    | Combine branches      | Join changes              |

### | rebase   | Reapply commits       | Clean history             |

### | switch   | Change branches       | Move between branches     |

### | tag      | Mark versions         | Label important commits   |


<<<<<<< HEAD
>>>>>>> new_branch
=======
>>>>>>> new_branch

