# Fundamentals
```git checkout another_branch_name``` 
git checkout can actually be used without the given branch name, checkingout without specification would set HEAD to be the current branch. 


**NOTE:** changes would be discarded.


```git checkout -b new_branch_name```


Adding the -b flag creates a new branch with the given name, similar to what ```git branch``` does. 


```git branch```



```git switch```


```git restore```
Introduced by Git 2.25.0, used instead of git reset from this version onward.


```git reset --hard [<commit>]```
Hard mode discarded all changes after ```<commit>```, this also resets the index. 


```git reset --soft```
This would leave all changed files as "changes to be committed" and same as ```git status``` would put.


```git merge``` 


# Additional
## Notes
1. Example use ``` git restore --staged <file>..." to unstage)```, if a file was named README.md from README, unstaging would revert the name back to README.