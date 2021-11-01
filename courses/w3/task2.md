# Reading

- [Git Tutorial for Beginners](https://academind.com/tutorials/git-the-basics)
- [Git cheat sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)


# Writing - Git Basics

- What is the difference between "git fetch" and "git pull"?
'git fetch' will not change the local repo and branch, use 'git merge' after 'git fetch' can get the same result compare with 'git pull'

- What is the difference between "git merge" and "git rebase"?


- Your changes yesterday have been merged, but it also introduces a new bug, the team agreed to remove it for now. What command to use?
git revert HEAD

- How to update the latest commit message in your local repo?
git fetch origin master:master_temp
git diff master_temp
git merge master_temp
git branch -d master_temp

- How to update the 2nd latest commit message in your local repo?
