#Git

Distributed means that every user has a full copy of the history.
Version Control System means that it's designed to keep records of changes, allow you to examine differences between changes (diffing), allow you to create separate sets of changes on the same information (branching), and allow you to bring separate changes together into one place (merging).

Git States

There are three states for your files to be in when you’re working with Git. These three states are: modified, staged and committed.

When you make changes to a file in your working directory, it is then modified, but these modifications are not stored in the codebase. When you stage the file, these changes are marked to be saved in the next commit. When you commit the file, these changes are finally stored in your codebase.

![](https://blog.udemy.com/wp-content/uploads/2015/08/image027.png)

$ git branch
*master

git status

$ git branch --no-merged
testing
