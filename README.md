## Developer-handbook

[![GitHub license](https://img.shields.io/github/license/Sambit650/git-command)](https://github.com/Sambit650/git-command/blob/main/LICENSE)

# git commands :
------

* Clone a Project : `git clone <url>`
* Push local branch to remote : `git push --set-upstream origin <b_name>`
* Create and checkout local branch : `git checkout -b <new_branch_name>`
* Create a local branch : `git branch <new_b_name>`
* Delete a local branch : `git branch -d <b_name>`
* Check all branch : `git branch`
* Switch to other branch : `git checkout <b_name>`
* Details of all commits : `git log`
* Check diff : `git diff`
* Separate the changes : `git stash / git stash apply` 
* Back to previous commit : `git reset —-soft HEAD^`
* Forcefully Back to previous commit : `git reset --hard HEAD^`
* Save and Quit commit : `:wq`
* Show hidden list : `ls -la`
* Push : `git push`
* Pull : `git pull`
* Push to a branch : `git push origin <b_name>`
* Set Remote Connection : `git remote add origin <git_link>`
* Git Config Global: `git config --global user.name "My Name"`
  * `git config --global user.email "myemail@example.com"`
* Git Config Local: `git config --local user.name "My Name"`
  * `git config --local user.email "myemail@gmail.com"`
* Git Config for a particular Project: `git config user.name "My Name"`
  * `git config user.email "email@gmail.com"`
* Delete git Config : `git rm -rf .git`
* Check Git Id Details : `git config --list`
* Create git ignore file : `touch .gitignore`
* Delete pod files : `pod deintegrate`
* Install Pod file : `pod install`
* Update Pod file : `pod update`
* Add `\`,which file contains Space : `\`
* Modify most recent commit : `git commit --amend`
* Undoing/Revert the changes : `git revert`
* Delete the Last commit from remote : `git reset —hard HEAD^`
  * commit the changes 
  * `git push -f`
* Remove individual stag file : `git reset <file_name>`
* Restore all Changes : `git restore .`
