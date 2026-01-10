# The Concept of bisect, diff and grep in GIT



1. The Concept of bisect \[Find the commit that caused a bug]
           git bisect helps you find exactly which commit introduced a bug by using a binary search method.

   		. git bisect start
   		. git bisect bad        	# current commit has bug
   		. git bisect good abc123  	# known good commit

   
   ---
2. The Concept of diff \[ To view Changes]
   	git diff shows what has changed in your code.
   		
   Command for diff
   		git diff   
   		git diff --staged  \[ To see staged changes]
   		git diff commit1 commit2 \[ To know the difference between commit1 and commit2 ]
   
   ---
3. The Concept of grep \[ To Search for some text inside the files]
   	git grep searches for a word or pattern inside tracked files in a Git repository.
   	
   	Command for grep
   				git grep "words to find out"
   				git grep "words to find out" file\_name.ext  \[ To find out something in specific files ]
   ---

## 

## Conclusion 



## | Command      | Purpose         | Simple Meaning              |

## | ------------ | --------------- | --------------------------- |

## | `git bisect` | Find bug source | Which commit broke the code |

## | `git diff`   | Show changes    | What changed in the code    |

## | `git grep`   | Search text     | Where a word exists in code |



## 



