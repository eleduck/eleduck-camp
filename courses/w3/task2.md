# Reading

- [Git Tutorial for Beginners](https://academind.com/tutorials/git-the-basics)
- [Git cheat sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)


# Writing - Git Basics

- What is the difference between "git fetch" and "git pull"?  
Git fetch only downloads new data from a remote repository but does not change the working directory.  
Git pull is shorthand for git fetch followed by git merge, git pull tries to merge remote changes with local ones.
- What is the difference between "git merge" and "git rebase"?
Git merge adds a new commit and preserves the history of the branch.  
Git rebase compresses all the changes into a single "path". Unlike merging, rebasing flattens history. 
- Your changes yesterday have been merged, but it also introduces a new bug, the team agreed to remove it for now. What command to use?  
If the team agreed, to remove the commit, we can use git reset double-dash hard and the HEAD to the previous commit, the push to the remote repo with the force option.
- How to update the latest commit message in your local repo?  
Use the "git commit" command with the double-dash amend option, we can update the latest commit message.
- How to update the 2nd latest commit message in your local repo?  
Use git rebase and git commit amend to update the 2nd latest commit message, firstly use git rebase dash "i" HEAD tilde 2, starts the rebase operation, then git will open vi editor, we can edit the 2nd latest commit line, replace pick with edit then save and exit, check the git log, we can see the line we just modified is the latest commit, then use git commit double-dash amend, we can update the commit message, then use git rebase double-dash continue to finish the rebase option.
