# Reading

- [Git Tutorial for Beginners](https://academind.com/tutorials/git-the-basics)
- [Git cheat sheet](https://www.atlassian.com/git/tutorials/atlassian-git-cheatsheet)


# Writing - Git Basics

- What is the difference between "git fetch" and "git pull"?
```
Git fetch can directly change the remote tracking branch, git pull cannot directly operate on the remote tracking branch, 
we must first switch back to the local branch and then create a new commit submission.
```
- What is the difference between "git merge" and "git rebase"?
```
merge will merge the public branch with your current commit to form a new commit submission; 
rebase will put the commit of your current branch at the end of the public branch
```
- Your changes yesterday have been merged, but it also introduces a new bug, the team agreed to remove it for now. What command to use?
```
git revert
```
- How to update the latest commit message in your local repo?
```
git rebase --continue
```
- How to update the 2nd latest commit message in your local repo?
```
git rebase -i HEAD~2
```
