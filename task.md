# Task 4.2 - Fix conflict (2)

## Discuss About Previous Task

After you done previous task, your log will be like the follow:

```
* (HEAD -> feature2) Task 4.1
|
|
* Merge branch 'feature2'
|\
| * (feature2) Task 4.2
| |
| * Task 4.1
* | Task 4.3
|/
* (feature1) Task 3
|
|
*  Task 2
|
|
*  Task 1
```

I hope you understand your log now.

`git revert` will revert to previous commit and create a new commit to save it.

Just checkout to "master" branch.

## Description

1. Commit current change to branch "feature2"
2. Checkout to branch "master"

- `git rebase`
- `git rebase --abort`
- `git rebase --continue`
- `git rebase --skip`
