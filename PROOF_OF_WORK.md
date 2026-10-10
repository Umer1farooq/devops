\# Proof of Work — DevOps Git Challenge



\## Git Commit History



Paste the output of `git log --oneline` here before submission.



\## Q1: Difference Between Git and GitHub



Git is a distributed version control system that tracks file changes and maintains project history locally. GitHub is a cloud platform that hosts Git repositories online. Git allows developers to commit, branch, and merge changes. GitHub enables collaboration through remote repositories, pull requests, and code reviews.



\## Q2: Three Git Architecture Stages



The Working Directory is where developers create and edit files. The Staging Area contains changes selected for the next commit using `git add`. The Local Repository stores committed snapshots and the project's version history. These three stages help developers control which changes are included in a commit.



\## Q3: Difference Between git stash pop and git stash apply



Both commands restore previously stashed changes to the working directory. `git stash pop` normally removes the stash entry after successfully applying it. `git stash apply` restores the changes but keeps the stash entry. Keeping the stash allows developers to reuse the same saved changes later.



\## Q4: Difference Between git fetch and git pull



The `git fetch` command downloads updates from a remote repository without integrating them into the current branch. This allows developers to review incoming changes first. The `git pull` command fetches updates and integrates them into the current branch, usually through a merge or rebase. Fetch is useful for reviewing changes, while pull is useful when you are ready to integrate them.



