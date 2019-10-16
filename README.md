# Github-commands

### 1) To clone the repository of a specific branch
 
```
git clone -b <branch-name> repository_url
```
#### For Example: 
* name of the branch to be cloned is 'feature/666/prototype' 
* The repository URL is 'https://github.com/xyz/abc

```
git clone -b feature/666/prototype https://github.com/xyz/abc
```

### 2) Check in which branch you are in

```
git branch
```
* The branch which is highlighted in Green color is your current branch that you are currently present on.

### 3) To create a branch from a branch

```
git checkout -b <sub-branch> branch
```
#### For Example:
  * name of the new branch to be created 'XYZ'
  * name of the branch ABC under which XYZ has to be created
```
git checkout -b XYZ ABC
```

### 4) To update the local repository from the remote repository

* Do a git fetch first
```
git fetch
```
* Do a merge command from the branch(ABC) from which you want to update

```
git merge origin/ABC
```

### 5) To push the changes to the remote repository
* Run the git add . command
```
git add .
```
* Run the git status command
```
git status
```
* Run the git commit command
```
git commit -m "feat: message"
```
* Run the push command
git push origin <branch-name>
  
#### For Example:
  * name of the branch to be which content is to be pushed 'XYZ'
```
git push origin XYZ
```
### 6) To delete a local branch

```
git branch -D <branch-name>
```
#### For Example:
* To delete a local branch XYZ come out of that branch and execute the command
```
git branch -D XYZ
```




