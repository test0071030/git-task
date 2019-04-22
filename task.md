# Task 4.2 - Fix conflict (2)

## Discuss About Previous Task

After you done previous task, your log will be like the follow:

```
* (HEAD -> feature2) Task 4.1
|
|
* (master, feature1) Task 3
|
|
*  Task 2
|
|
*  Task 1
```

I hope you understand your log now.

```
* (HEAD -> master) Merge branch 'feature2'
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

Just checkout to "master" branch.

## Description

1. Commit current change to branch "feature2"
2. Checkout to branch "master"

- `git revert`
