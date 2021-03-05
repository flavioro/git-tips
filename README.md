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

### Switch to a Branch In Your Local Repo
```
git checkout my-branch-name
```

### Push to a Branch
If your local branch does not exist on the remote, run either of these commands:
```
git push -u origin my-branch-name
```
git push -u origin HEAD
- NOTE: HEAD is a reference to the top of the current branch, so it's an easy way to push to a branch of the same name on the remote. This saves you from having to type out the exact name of the branch!

- If your local branch already exists on the remote, run this command:
```
git push
```
