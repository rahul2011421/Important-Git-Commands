# Commonly Used Git Commands

Here is a list of Git commands that I have used 99% of the time:


0. 𝗴𝗶𝘁 𝗶𝗻𝗶𝘁: Initializes a new Git repository.
1. 𝗴𝗶𝘁 𝗰𝗹𝗼𝗻𝗲 [𝘂𝗿𝗹]: Creates a local copy of a remote repository.
2. 𝗴𝗶𝘁 𝘀𝘁𝗮𝘁𝘂𝘀: Displays the state of the working directory and staging area.
3. 𝗴𝗶𝘁 𝗮𝗱𝗱 [𝗳𝗶𝗹𝗲]: Adds a file to the staging area.
4. 𝗴𝗶𝘁 𝗿𝗲𝘀𝗲𝘁 [𝗳𝗶𝗹𝗲]: Unstages a file while retaining the changes.
5. 𝗴𝗶𝘁 𝗱𝗶𝗳𝗳 --𝘀𝘁𝗮𝗴𝗲𝗱: Shows differences between the staging area and the last commit.
6. 𝗴𝗶𝘁 𝗰𝗼𝗺𝗺𝗶𝘁 -𝗺 "[𝗺𝗲𝘀𝘀𝗮𝗴𝗲]": Records staged changes with a descriptive message.
7. 𝗴𝗶𝘁 𝗯𝗿𝗮𝗻𝗰𝗵: Lists all local branches.
8. 𝗴𝗶𝘁 𝗰𝗵𝗲𝗰𝗸𝗼𝘂𝘁 -𝗯 [𝗻𝗮𝗺𝗲]: Creates and switches to a new branch.
9. 𝗴𝗶𝘁 𝗹𝗼𝗴: Displays commit history.
10. 𝗴𝗶𝘁 𝗿𝗲𝗺𝗼𝘁𝗲 𝗮𝗱𝗱 [𝗿𝗲𝗳] [𝘂𝗿𝗹]: Adds a new remote repository.
11. 𝗴𝗶𝘁 𝗽𝘂𝘀𝗵 [𝗮𝗹𝗶𝗮𝘀] [𝗯𝗿𝗮𝗻𝗰𝗵]: Uploads local branch commits to a remote repository.
12. 𝗴𝗶𝘁 𝗽𝘂𝗹𝗹: Fetches and merges changes from the remote to the local repository.
13. 𝗴𝗶𝘁 𝘀𝘁𝗮𝘀𝗵: Temporarily stores modified tracked files.
14. 𝗴𝗶𝘁 𝘀𝘁𝗮𝘀𝗵 𝗽𝗼𝗽: Restores the most recently stashed files.
15. 𝗴𝗶𝘁 𝘀𝘁𝗮𝘀𝗵 𝗱𝗿𝗼𝗽: Discards the most recently stashed changeset.
16. 𝗴𝗶𝘁 𝗿𝗲𝗯𝗮𝘀𝗲 [𝗯𝗿𝗮𝗻𝗰𝗵]: Reapplies commits on top of another base tip.
17. 𝗴𝗶𝘁 𝗿𝗲𝗯𝗮𝘀𝗲 -𝗶 𝗛𝗘𝗔𝗗~<𝗻>: Starts an interactive rebase for the last n commits.
18. 𝗴𝗶𝘁 𝗿𝗲𝘀𝗲𝘁 --𝗵𝗮𝗿𝗱 [𝗰𝗼𝗺𝗺𝗶𝘁]: Resets the working directory to a specified commit.
19. 𝗴𝗶𝘁 𝗹𝗼𝗴 𝗯𝗿𝗮𝗻𝗰𝗵𝗕..𝗯𝗿𝗮𝗻𝗰𝗵𝗔: Shows commits on branchA that are not on branchB.
20. 𝗴𝗶𝘁 𝗱𝗶𝗳𝗳 𝗯𝗿𝗮𝗻𝗰𝗵𝗕...𝗯𝗿𝗮𝗻𝗰𝗵𝗔: Displays differences between two branches.
21. 𝗴𝗶𝘁 𝘀𝗵𝗼𝘄 [𝗦𝗛𝗔]: Shows the changes in a specific commit.
22. 𝗴𝗶𝘁 𝗰𝗼𝗻𝗳𝗶𝗴 --𝗴𝗹𝗼𝗯𝗮𝗹 𝗰𝗼𝗿𝗲.𝗲𝘅𝗰𝗹𝘂𝗱𝗲𝘀𝗳𝗶𝗹𝗲 [𝗳𝗶𝗹𝗲]: Sets up a global file for ignoring files.



**-----------------------------------------------------------------------------------**
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
29. 
