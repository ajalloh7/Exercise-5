# Exercise-5
Answers to the questions
How do you see the files changed within each commit from git log?
Git log shows all the commit messages and the revision hash. The git log also shows the files changed.
Each time there is a commit, I noticed a commit ID with a very long name about 40 characters.
How do you see the contents of what changed within each file from the git log?
The content will show the entire history of the file including history beyond renames and with diffs for each change.
You can also see when a specific line of code inside a file was changed.
What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflice content.
HEAD is the reference to the last commit in the currently check-out branch. The HEAD is also seen as the "current branch". When you switch branches with git checkout, the HEAD revision changes to point to the tip of the new branch.
