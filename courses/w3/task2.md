# Reading

- [Git Tutorial for Beginners](https://academind.com/tutorials/git-the-basics)
- [Git cheat sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)

# Writing - Git Basics

- What is the difference between "git fetch" and "git pull"?
  git pull = git fetch + git merge
- What is the difference between "git merge" and "git rebase"?
  git merge has history commit ,git rebase need solve conflict
- Your changes yesterday have been merged, but it also introduces a new bug, the team agreed to remove it for now. What command to use?
  git revert
- How to update the latest commit message in your local repo?
  git fetch origin branchName
  git checkout HEAD
- How to update the 2nd latest commit message in your local repo?
  git fetch origin branchName
  git checkout HEAD^
