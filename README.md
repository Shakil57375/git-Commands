# Github commands

- ### To check the present working directory type

```
pwd
```

- ### To create a new file type :

```
touch [file Name]
```

- ### To check how many file or what's the files you have type:

```
ls
```

- ### To check what git tracking what not type:

```
git status
```

- ### To check the lists of files including hidden files type:

```
git status
```

- ### To add something on the git or available for tracking of git just simply type type:

```
git add [file name] // to add specific file
git add --all // to add all the files on the folder
git add . // to add all the file [work as same as git add -all]
```

- ### use the command to know the git commit history:

```
git log
git log --oneline [to have one line of history]
```

- ### to have the previous commit back or to have what have you done on your previous commit you have to do this:

```
- at first copy the id of previous commit from (git commit --online)
- then type [git reset --hard (previous commits id)]
```

#### you will not get back the commits you have been switched on by using git log/ git log --oneline. But if you want to have all the commit history you can type 👍

```
git reflog
```

### to check how many branches you have or you have create type:

```
git branch --list
```

### to create a branch type:

```
git branch [branch name]
```

### to switch from one branch to another type:

```
git switch [branch name]
```

### checkout this documentation of chat-gpt for more information about create, rename, delete , recover a deleted branch and many more.

```
https://chat.openai.com/share/f076ba8e-62ac-4249-a039-d50f7dfe3fc4
```
### to delete a branch type 👍:
```
git branch -d [branch name]
```

### to edit a branch name type :
```
git branch -m [old branch name ] [new branch name]
```


