# P3 – Feature-branch Git workflow

## Objective
Practise creating a branch, committing a change, and merging it.

## Commands
```bash
git switch -c feature/update-bio
# Make a small change to a project file
git status
git add .
git commit -m "Add bio page content"
git switch main
git merge feature/update-bio
git push
```

## Expected result
The feature branch is merged into `main`. Use `git log --oneline --graph --all` to inspect the history.
