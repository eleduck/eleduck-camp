# Reading

- [Git Tutorial for Beginners](https://academind.com/tutorials/git-the-basics)
- [Git cheat sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)


# Writing - Git Basics

- What is the difference between "git fetch" and "git pull"?
  `git fetch` is to synchronize the status of remote files to the local. `git pull` is to pull remote fills to the local.

- What is the difference between "git merge" and "git rebase"?
  `git merge` will record all commit histories in the order of commit. `git rebase` will rollback all commits first, merge then base branch, then merge, and finally restore the rolled back commits.

- Your changes yesterday have been merged, but it also introduces a new bug, the team agreed to remove it for now. What command to use?
  Use `git log` get commit code, then use `git revert -n **` to rollback commit of before.

- How to update the latest commit message in your local repo?
  `git commit --ament -m "***"`

- How to update the 2nd latest commit message in your local repo?
  Use `git rebase -i HEAD~2` to enter the editing state, then edit the second information.
