### Git Commands 🛠

👉 **Getting Started** 😄😄😄

## Git Setup- 
It is time to setup the **git Environment**.
You should have to do these things only once on any given computer; they’ll stick around between upgrades.
You can also change them at any time by running through the commands again.
<br><br>
🛠 Global git config:
```
$ git config --global user.name "My Name"
$ git config --global user.email "myemail@example.com" 
 ```
 <br><br>
 🛠 Local git config:
 ```
$ git config --local user.name "My Name"
$ git config --local user.email "myemail@gmail.com"
 ```
 <br><br>
  🛠 Individual git config:
  ```
 $ git config user.name "My Name"
 $ git config user.email "email@gmail.com"
  ```
  <br><br>
    🧐 Check config Details:
  ```
 $ git config --list
  ```
  <br><br>
  😡 Delete git config:
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

👉 Git Checkout:
<br>
The git checkout command is used to switch branches and check content out into your working
directory.<br>
```
$ git checkout <new_branch_name>
```
<br><br>
👉 Create a new branch and checkout to this branch:
* This is a smart way to create a branch 😎
```
$ git checkout -b <new_branch_name>
```

<br><br>
👉 Check all existing branches:
```
$ git branch
```
<br><br>
👉 Create a new branch:
```
$ git branch <new_branch_name>
```
<br><br>
👉 Delete a branch:
```
$ git branch -d <b_name>
```
<br><br>
👉 Rename a branch:
```
$ git branch -m <old_name> <new_name>
```
<br><br>
👉 Create a new git repository 
```
$ git init
```

## Working with Remotes
To be able to collaborate on any Git project, you need to know how to manage your remote repositories.
Remote repositories are versions of your project that are hosted on the Internet or network somewhere.
<br><br>
👉 Add remote origin:
```
$ git remote add origin <git_link>
```
<br><br>
👉 Push a local branch to remote:
```
$ git push --set-upstream origin <b_name>
```
<br><br>
👉 Push:
```
$ git push
```
<br><br>
👉 Forcefully Push:
```
$ git push -f
```
<br><br>
👉 Push  a branch to remote origin:
```
$ git push origin <branch_name>
```
<br><br>
👉 Pull:
```
$ git pull
```
<br><br>
## Staging and Unstaging Files
👉 Add a file to stage:
```
$ git add <file_name>
```
<br><br>
👉 Add all files to stage:
```
$ git add .
```
<br><br>
👉 Remove individual file frome stage:
```
$ git reset <file_name>
```
<br><br>
👉 Commit:
```
$ git commit -m "commit_message"
```
<br><br>
👉 Modify most recent commit message:
```
$ git commit --amend
```
<br><br>
😄 Add any particular commit to a PR/MR: 
```
$ git cherry-pick <commit_hashcode>
```
<br><br>
👉 Git Reset:
If you want to remove the last commit from the current branch, But want to keepnthe file changes.
this command will help you👇
```
$ git reset --soft HEAD^
```
<br><br>
If you want to remove the last commit with changes,The changes won't stay in your working tree.
then blow command will help you👇
```
$ git reset --hard HEAD^
```
<br><br>
👉 Delete last commit From remote:
```
// remove the commit
$ git reset --hard HEAD^
// commit your changes
$ git commit -m "commit_message"
// push forcefully
$ git push -f
```
<br><br>
🦹 Undoing things with git reset
```
$ git restore .
```
<br><br>
🦹🏻 Undoing/Revert the changes:
```
$ git revert
```
<br><br>
🧑‍💻 Check repository history:
```
$ git log
```
<br><br>
🧑‍💻 To see only the commits of a certain author:
```
$ git log --author=<author_name>
```
<br><br>
🧑‍💻 Before merging changes, Preview:
```
$ git diff
$ git diff <source_branch> <target_branch>
```
<br><br>
🧑‍💻 Stashing:
```
$ git stash
$ git stash apply
```
<br><br>
🧑‍💻 Release Tag:
```
$ git tag <tag_name> <commit_id>
```
<br><br>
🧑‍💻 Create a file with command:
```
$ touch <file_name>
```
<br><br>
🧑‍💻 To see the art tree of all the branches:
```
$ git log --graph --oneline --decorate --all
```
<br><br>
## Merging 
🧑‍💻 Merge two local branches: 
```
$ git merge <branch_name>
```
<br><br>
🧑‍💻 Abort the merge:
```
$ git merge --abort
```
<br><br>
* Save and Quit commit : `:wq`
* Show hidden list : `ls -la`
* Add `\`,which file contains Space


#### Credits:

**©** **Sambit Das** | **2021**

