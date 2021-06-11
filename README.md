1. How do you see the files changed within each commit from git log?

answer''Using git log --follow -p bar will show the file's entire history, including any changes to the file when it was known as foo . The -p option ensures that diffs are included for each change.


2. How do you see the contents of what changed within each file from the git log?

answer Using git log --follow -p bar will show the file's entire history, including any changes to the file when it was known as foo . The -p option ensures that diffs are included for each change.

3.What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict

answer-The HEAD in Git is the pointer to the current branch reference, which is in turn a pointer to the last commit you made or the last commit that was checked out into your working directory. That also means it will be the parent of the next commit you do.