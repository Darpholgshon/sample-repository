# Sample Repository
Sample Repository for demonstrating Git functions

# History

* No release versions yet.

# Instructions to try out rebasing.

1. create repository with default `README.md` and `.gitignore` (Java) files.
2. create two feature branches.
3. Checkout `feature/gitignore-changes` feature branch and change the `.gitignore` file to change to ignore IntelliJ project files.
4. push back to branch, create PR and merge to master.
5. checkout `feature/readme-improvements` feature branch.
6. modified `README.md`, and also made same changes to `.gitignore` file, but with a different comment.
7. commit to branch
8. checkout `master` and pull latest
9. checkout `feature/readme-improvements`
10.  git rebase master
11. Merge conflict on `.gitignore` file - resolve conflict.
12. git rebase continue
13. git pull
14. git push
