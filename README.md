# Amend-Git

The git commit --amend command is a convenient way to modify the most recent commit. It is not advisable to amend public commits.

```

1. Create a Python file
$ vi hello.py
$ vi main.py

2. Commit hello.py
$ git add hello.py
$ git commit 

3. Realize you forgot to add the changes from main.py 
$ git add main.py 
$ git commit --amend --no-edit

The --no-edit flag will allow you to make the amendment to your commit without changing its commit message. 

```
