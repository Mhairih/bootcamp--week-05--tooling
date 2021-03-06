# Going back
1) **Use `git checkout {ref}` to rewind your project files**

	Use `git reflog` to see recent history and commit references
	
	Choose a commit to go back to (rewind) and check it out. 

	This can be done by referencing the commit reference `git checkout {ref}` or using the `git checkout HEAD~{n}` syntax to go back `n` commits.

	Check the files are in the state you expect, i.e. old versions.
	
1) **Go back to most recent commit**

	Use `git checkout master` or `git switch -` to get back to the most recent commit.

*`HEAD~` is a shorthand reference for previous commit, as in "one commit ago".*
