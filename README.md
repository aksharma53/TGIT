# TGIT

- flowchart->`working area`>`staging area(add)`>`repository(commit)`\

- adding and commiting\
  - `git commit -a -m "msg"` shortcut for add and commit\

 

- branching
  - `git branch -D cool` switch outside of repo u have to deleted\
  -  `git switch -c "branch name"` shortcut for creating and switching branch\

- stashing
  - `git stash` \
  - `git stash pop`\
  - `git stash list`\
  - `git stash clear`\
  - `git stash drop {id}` delete specific stash\

- account\
  - `git config --global user.name "analystabhishek"` giving username\
  - `git config --global user.email "abhishekalacrity@gmail.com"` giving email\
  - `git config --list` show username and email\
  - `git log --oneline `  show what all user done commit\
  - `git log --author="alphasaurs"` to show what this user done commit\

- checkout\
  - `git checkout {commit hash id}`\
  - `git checkout HEAD~1` switch to previous commit\
  - `git switch -` switch to previous branch\



`git diff `difference between working and staging area\
`git diff --staged `difference between staging and repository\
`git diff HEAD`difference between repo and working area\
`git rm file_name.txt `delete file both working and repo\
`git mv file_name folder`move file to folder\
`git mv file_name filename`rename \
`git commit -am "cool"`get directly commit\
`git checkout -- file_name`undo the action after adding in working copy \
`git checkout commit_id -- file_name `undo the action after commiting in working copy \
`git reset HEAD file_name`moving file from staged to unstaged area\


- github

`git remote add origin repo_link`
`git remote`
`git push -u cool master`
//save file in .gitignore so that it is not tracked



- update 
git remote add upstream repo_link\
git pull upstream master\

