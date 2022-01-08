**GIT PLAYGROUND...**

`1`. How can I undo git reset --hard HEAD~1

```
$ git init
Initialized empty Git repository in .git/

$ echo "testing reset" > file1
$ git add file1
$ git commit -m 'added file1'
Created initial commit 1a75c1d: added file1
 1 files changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 file1

$ echo "added new file" > file2
$ git add file2
$ git commit -m 'added file2'
Created commit f6e5064: added file2
 1 files changed, 1 insertions(+), 0 deletions(-)
 create mode 100644 file2

$ git reset --hard HEAD^
HEAD is now at 1a75c1d... added file1

$ cat file2
cat: file2: No such file or directory

$ git reflog
1a75c1d... HEAD@{0}: reset --hard HEAD^: updating HEAD
f6e5064... HEAD@{1}: commit: added file2

$ git reset --hard f6e5064
HEAD is now at f6e5064... added file2

$ cat file2
added new file
```
