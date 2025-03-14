CONFIG
git config --list
git config --global user.name "Giga Kvachakhia"
git config --global user.email "stalkerglac@gmail.com"
git config --local user.name "Giga Kvachakhia"
git config --local user.email "stalkerglac@gmail.com"

RESET
git reset --soft HEAD~1
git reset --mixed HEAD~1 (default)
git reset --hard HEAD~1

CHECKOUT
git checkout <commit-hash> (detached)

CLEAN
git clean --dry-run (only warn)
git clean -fd (file + dir)

BRANCH & MERGE
git checkout master + git merge feature
a. fast-forward (no commits before)

PULL & FETCH
git branch -r (origin/master)
git pull (fetch + merge) -> [fetch to origin] + [merge to branch]

Squash and Merge
Rebase and Merge
