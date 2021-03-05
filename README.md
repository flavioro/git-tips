# git-tips
Github, tips, tricks etc

![](http://gabsferreira.com/content/images/2021/01/guia-git-e-github-37585.png)

### How do I force “git pull” to overwrite local files?
```
git reset --hard origin/master
```
REFERENCE: https://stackoverflow.com/questions/1125968/how-do-i-force-git-pull-to-overwrite-local-files


### List All Branches
NOTE: The current local branch will be marked with an asterisk (*).

- To see local branches, run this command:
```git branch```
- To see remote branches, run this command:
```git branch -r```
- To see all local and remote branches, run this command:
```git branch -a```

### Create a New Branch
- Run this command (replacing my-branch-name with whatever name you want):
```
git checkout -b my-branch-name
```
- You're now ready to commit to this branch.

