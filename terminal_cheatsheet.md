# Terminal cheatsheet to use

```
Important terminal commands:
```


* `mkdir` - creates new folder
* `touch` - creates new file
* `open` - opens files
* `mv` - move files
* `cp` - copy files
* `cp -r` - copy directory
* `rm` - delete (remove) file
* `rm - r` - delete directory
* `cd` - change directory
* `ls` - list folders and files
* `ls -l` - list folders and files, along with permissions and other info
* `ls -a` - list of folders and files, including hidden files
* `ls -al` - combines `ls -a` and `ls-l`
* `pwd` - tells us our current directory location
* `.` - current directory
* `..` - parent directory

> Note: Be VERY careful deleting files/directories. These cannot be recovered

```
Important Git commands:
```

* `git init` - initialise Git in the current directory
* `git status` - lets us know which files have been modified (on stage)
* `git add` - tells git to start tracking file (adds to stage)
* `git commit -m" "` - commits changes (add brief description between quotemarks)
* `git log` - gives a history of the commits made
* `git revert` - rolls back a specific commit (add ID of commit after command - found in log)


On Github, to add the repository go to the `+` icon in the top-right corner, and select `New repository`.
Give the repository a name and description if needed, and make it public. 
Click `Create repository` and you will be given some code to copy into the terminal to create the repository.

Once the repository has been added to your Github, use `git push` after committing any edits to push the edits up to Github