## Developer-handbook

---------------

# git commands :

* Clone a Project : `git clone <url>`
* Push local branch to remote : `git push --set-upstream origin <b_name>`
* Create and checkout local branch : `git checkout -b <new_branch_name>`
* Create a local branch : `git branch <new_b_name>`
* Delete a local branch : `git branch -d <b_name>`
* Check all branches : `git branch`
* Switch to other branch : `git checkout <b_name>`
* Details of all commits : `git log`
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
* Git Config Global : `git config --global user.name "My Name"`
  * `git config --global user.email "myemail@example.com"`
* Git Config Local : `git config --local user.name "My Name"`
  * `git config --local user.email "myemail@gmail.com"`
* Git Config for a particular Project : `git config user.name "My Name"`
  * `git config user.email "email@gmail.com"`
* Delete git Config : `git rm -rf .git`
* Check Git Config Details : `git config --list`
* Create git ignore file : `touch .gitignore`
* Add `\`,which file contains Space : `\`
* Modify most recent commit : `git commit --amend`
* Undoing/Revert the changes : `git revert`
* Delete the Last commit from remote : `git reset —hard HEAD^`
  * commit the changes 
  * `git push -f`
* Remove individual stag file : `git reset <file_name>`
* Restore all Changes : `git restore .`

<hr>

# Pod Commands :

* Delete pod files : `pod deintegrate`
* Install Pod file : `pod install`
* Update Pod file : `pod update`

<hr>

# HTTP Response and Error Codes :

* 200 - Everything is OK
* 201 - Created Successfully
* 202 - Accepted
* 204 - No Content
* 301 - Moved Permanently
* 302 - Found
* 303 - See Other
* 304 - Not Modified
* 307 - Temporary Redirect
* 308 - Resume Incomplete 
* 400 - Bad Request
* 401 - Unauthorized
* 403 - Forbidden
* 404 - Not Found
* 405 - Method Not Allowed
* 408 - Request Timeout
* 409 - Conflict 
* 410 - Gone
* 411 - Length Required 
* 412 - precondition Failed
* 413 - Payload Too Large
* 416 - Requested Range Not Statisfiable
* 429 - Too many Request
* 500 - Internal Server Error
* 502 - Bad Gateway
* 503 - Service unavailable server error
* 504 - Gateway Timeout* 200 - Everything is OK
* 201 - Created Successfully
* 202 - Accepted
* 204 - No Content
* 301 - Moved Permanently
* 302 - Found
* 303 - See Other
* 304 - Not Modified
* 307 - Temporary Redirect
* 308 - Resume Incomplete 
* 400 - Bad Request
* 401 - Unauthorized
* 403 - Forbidden
* 404 - Not Found
* 405 - Method Not Allowed
* 408 - Request Timeout
* 409 - Conflict 
* 410 - Gone
* 411 - Length Required 
* 412 - precondition Failed
* 413 - Payload Too Large
* 416 - Requested Range Not Statisfiable
* 429 - Too many Request
* 500 - Internal Server Error
* 502 - Bad Gateway
* 503 - Service unavailable server error
* 504 - Gateway Timeout
