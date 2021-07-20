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
## Git Branching and Merging
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
👉 Check all existing branches:
```
$ git branch
```
<br><br>
👉 Create a new branch:
```
$ git branch -b <new_branch_name>
```
<br><br>
👉 




* Push local branch to remote : `git push --set-upstream origin <b_name>`
* Create a local branch : `git branch <new_b_name>`
* Delete a local branch : `git branch -d <b_name>`
* Check all branches : `git branch`
* Switch to other branch : `git checkout <b_name>`
* Repository history : `git log`
* To See only the commits of a certain author : `git log --author=<author_name>`
* Check diff : `git diff`
* Before merging changes, Preview : `git diff <source_branch> <target_branch>`
* Separate the changes : `git stash / git stash apply` 
* Back to previous commit : `git reset —-soft HEAD^`
* Forcefully Back to previous commit : `git reset --hard HEAD^`
* Save and Quit commit : `:wq`
* Show hidden list : `ls -la`
* Push : `git push`
* Pull : `git pull`
* Push a branch to remote origin : `git push origin <b_name>`
* Set Remote origin : `git remote add origin <git_link>`
* 

* 
* Create git ignore file : `touch .gitignore`
* Add `\`,which file contains Space : `\`
* Modify most recent commit : `git commit --amend`
* Undoing/Revert the changes : `git revert`
* Delete the Last commit from remote : `git reset —hard HEAD^`
  * commit the changes 
  * `git push -f`
* Remove individual stag file : `git reset <file_name>`
* Restore all Changes : `git restore .`
* Release tag : `git tag <tag_name> <commit_id>`
* To see the art tree of all the branches : `git log --graph --oneline --decorate --all`
* Merge two local branches :- `git merge <branch_name>`
* Abort the Merge :- `git merge --abort`
* Add any particular commit to a PR/MR :- `git cherry-pick <commit_hashcode>`
