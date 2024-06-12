# Commonly Used Git Commands

Here is a list of Git commands that I have used 99% of the time:

1. **git diff**: Show file differences not yet staged.
2. **git commit -a -m "commit message"**: Commit all tracked changes with a message.
3. **git commit --amend**: Modify the last commit.
4. **git status**: Show the state of your working directory.
5. **git add file_path**: Add file(s) to the staging area.
6. **git checkout -b branch_name**: Create and switch to a new branch.
7. **git checkout branch_name**: Switch to an existing branch.
8. **git checkout <commit>**: Switches the working directory to a specific commit.
9. **git push origin branch_name**: Push a branch to a remote.
10. **git pull**: Fetch and merge remote changes.
11. **git fetch**: Fetch changes from the remote repository without merging.
12. **git rebase -i**: Rebase interactively, rewrite commit history.
13. **git rebase branch_name**: Rebase the current branch onto another branch.
14. **git clone**: Create a local copy of a remote repo.
15. **git merge**: Merge branches together.
16. **git log --stat**: Show commit logs with stats.
17. **git stash**: Stash changes for later.
18. **git stash pop**: Apply and remove stashed changes.
19. **git show commit_id**: Show details about a commit.
20. **git reset HEAD~1**: Undo the last commit, preserving changes locally.
21. **git branch -D branch_name**: Delete a branch forcefully.
22. **git reset**: Undo commits by moving branch reference.
23. **git revert commit_id**: Create a new commit that undoes the changes of a specific commit.
24. **git cherry-pick commit_id**: Apply changes from a specific commit.
25. **git branch**: Lists branches.
26. **git reset --soft HEAD^**: Undo the last commit, but keep the changes.
27. **git reset --hard**: Resets everything to a previous commit, erasing all uncommitted changes.
28. **git branch --set-upstream-to remote_branch**: Sets the upstream branch to the specified remote branch.
