## cheat_sheet
Set of commands or code bits I often have to google e.g. bc ordering of arguments is confusing.

# Git

- create a new branch base off the current branch: git checkout -b branch_name
- checkout an existing branch from remote: git checkout --track remote_name/branch_name
- add a remote: git remote add extensions url_git_repo
- push branch to a specific remote: git push remote_name branch_name. To set a remote by default: git push -u remote_name branch_name
- amazing: git stash has a history. To recover a file: git diff stash@{i}^1 stash@{i} -- file_name (to know what i, do git stash list)
- to not show untracked files: git status --untracked-files=no
  


