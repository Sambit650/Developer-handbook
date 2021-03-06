### Git Commands π 

π **Getting Started** πππ

## Git Setup- 
It is time to setup the **git Environment**.
You should have to do these things only once on any given computer; theyβll stick around between upgrades.
You can also change them at any time by running through the commands again.
<br><br>
π  Global git config:
```
$ git config --global user.name "My Name"
$ git config --global user.email "myemail@example.com" 
 ```
 <br><br>
 π  Local git config:
 ```
$ git config --local user.name "My Name"
$ git config --local user.email "myemail@gmail.com"
 ```
 <br><br>
  π  Individual git config:
  ```
 $ git config user.name "My Name"
 $ git config user.email "email@gmail.com"
  ```
  <br><br>
    π§ Check config Details:
  ```
 $ git config --list
  ```
  <br><br>
  π‘ Delete git config:
  ```
 $ git rm -rf .git
  ```
<br><br>
## Cloning an Existing Repository
If You want to get a copy of an existing Git repository. Follow the below command
```
$ git clone <url>
```
## Git Branching
The git branch command is actually something of a branch management tool. It can list the
branches you have, create a new branch, delete branches and rename branches.

π Git Checkout:
<br>
The git checkout command is used to switch branches and check content out into your working
directory.<br>
```
$ git checkout <new_branch_name>
```
<br><br>
π Create a new branch and checkout to this branch:
* This is a smart way to create a branch π
```
$ git checkout -b <new_branch_name>
```

<br><br>
π Check all existing branches:
```
$ git branch
```
<br><br>
π Create a new branch:
```
$ git branch <new_branch_name>
```
<br><br>
π Delete a branch:
```
$ git branch -d <b_name>
```
<br><br>
π Rename a branch:
```
$ git branch -m <old_name> <new_name>
```
<br><br>
π Create a new git repository 
```
$ git init
```

## Working with Remotes
To be able to collaborate on any Git project, you need to know how to manage your remote repositories.
Remote repositories are versions of your project that are hosted on the Internet or network somewhere.
<br><br>
π Add remote origin:
```
$ git remote add origin <git_link>
```
<br><br>
π Push a local branch to remote:
```
$ git push --set-upstream origin <b_name>
```
<br><br>
π Push:
```
$ git push
```
<br><br>
π Forcefully Push:
```
$ git push -f
```
<br><br>
π Push  a branch to remote origin:
```
$ git push origin <branch_name>
```
<br><br>
π Pull:
```
$ git pull
```
<br><br>
## Staging and Unstaging Files
π Add a file to stage:
```
$ git add <file_name>
```
<br><br>
π Add all files to stage:
```
$ git add .
```
<br><br>
π Remove individual file frome stage:
```
$ git reset <file_name>
```
<br><br>
π Commit:
```
$ git commit -m "commit_message"
```
<br><br>
π Modify most recent commit message:
```
$ git commit --amend
```
<br><br>
π Add any particular commit to a PR/MR: 
```
$ git cherry-pick <commit_hashcode>
```
<br><br>
π Git Reset:
If you want to remove the last commit from the current branch, But want to keepnthe file changes.
this command will help youπ
```
$ git reset --soft HEAD^
```
<br><br>
If you want to remove the last commit with changes,The changes won't stay in your working tree.
then blow command will help youπ
```
$ git reset --hard HEAD^
```
<br><br>
π Delete last commit From remote:
```
// remove the commit
$ git reset --hard HEAD^
// commit your changes
$ git commit -m "commit_message"
// push forcefully
$ git push -f
```
<br><br>
π¦Ή Undoing things with git reset
```
$ git restore .
```
<br><br>
π¦Ήπ» Undoing/Revert the changes:
```
$ git revert
```
<br><br>
π§βπ» Check repository history:
```
$ git log
```
<br><br>
π§βπ» To see only the commits of a certain author:
```
$ git log --author=<author_name>
```
<br><br>
π§βπ» Before merging changes, Preview:
```
$ git diff
$ git diff <source_branch> <target_branch>
```
<br><br>
π§βπ» Stashing:
```
$ git stash
$ git stash apply
```
<br><br>
π§βπ» Release Tag:
```
$ git tag <tag_name> <commit_id>
```
<br><br>
π§βπ» Create a file with command:
```
$ touch <file_name>
```
<br><br>
π§βπ» To see the art tree of all the branches:
```
$ git log --graph --oneline --decorate --all
```
<br><br>
## Merging 
π§βπ» Merge two local branches: 
```
$ git merge <branch_name>
```
<br><br>
π§βπ» Abort the merge:
```
$ git merge --abort
```
<br><br>
* Save and Quit commit : `:wq`
* Show hidden list : `ls -la`
* Add `\`,which file contains Space


#### Credits:

**Β©** **Sambit Das** | **2021**

