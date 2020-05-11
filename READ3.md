# Git

*it is a DVCS that stores data in a file system made up of snapshots.* 
*multiple developers can work on the same code, it gives you the ability to view, apply and remove files.*
*Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it*

*Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit*
## Cloning
*it is the creation of a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL.*
```
$ git clone https://github.com/test
```
### Check File Status
To determine the state of files, utilize the git status command:
```
$ git status
```
***Note that This information indicates which branch you’re on and states “working directory clean,” which means that files have tracked or modified status at the moment.***
### Tracking and Staging a New File
* Single File
```
$ git add filename
```
 ### Tracking all Files
```
$ git add .
```
### Committing a File
```
$ git commit -m “made change x,y,z”
```

### Committing All Changes
```
$ git commit -a
```

### Pushing Changes
```
$ git push origin master
```
