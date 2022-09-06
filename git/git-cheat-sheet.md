# Git Cheat Sheet

## Remove Commit History

1.  Checkout

    `git checkout --orphan latest_branch`
2.  Add all the files

    `git add -A`
3.  Commit the changes

    `git commit -am "commit message"`
4.  Delete the branch

    `git branch -D main`
5.  Rename the current branch to main

    `git branch -m main`
6.  Finally, force update your repository

    `git push -f origin main`

## Git Upstream

Useful when typing _`git pull`_ instead of typing _`git pull origin master`_&#x20;

```
git push -u origin <branch name>
```
