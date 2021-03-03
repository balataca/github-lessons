# github-lessons

## Types of Branches/Commits
* Feature (new functionality)
* Fix (bug fixes)
* Refactor
* Chore (Dependecy addition or project related commits)
## Commands

Get origin changes
```
git pull
```

Get origin branches
```
git fetch
```

Create a Branch  
```
git branch feature/name-of-the-branch
```

Checkout a branch
```
git checkout feature/name-of-the-branch
```

Push a new branch to origin
```
git push --set-upstream origin feature/name-of-the-branch
```

Stash changes:
```
git stash
```

Pop stash:
```
git stash pop
```

## Commit Template

```
prefix: short summary of changes

Longer message body explaining what's been changed

Issue: #number-of-the-issue
```

Example:
```
feature: adds a new header to start page

Adds a header to new index.html of
experience page

Issue: #4
```

## Git Flow
1. Pull the most recent changes in the repository
2. Create a branch of what you will be working on
3. Before commit always pull again
4. Commit your changes in atomic style
5. Push your new branch to origin
6. Make a pull request for merging into main
7. Merge changes
