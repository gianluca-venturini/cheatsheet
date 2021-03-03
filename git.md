## Git rebase

- `git rebase origin/master` rebase current branch on master
- `git rebase -i` interactive rebase

### Solving rebase conflcts
- `git checkout --ours -- <PATHS>` select changes on `master` branch (if rebasing on master)
- `git checkout --theirs -- <PATHS>` select changes on our branch
