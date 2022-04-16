# Git most Used Command

### To create a Repository:

- You can initialize a proyect folder as a git repository.
  `$ git init`
  ```
  git init
  ```
- You can download the repository into your local storage.
  `$ git clone "URL repo"`

### Remote Repositories.

- Display the connected remote repositories.
  `$ git remote`
- You can to connect to remote repository.
  `$ git remote add origin "URL"`
- You can to push all the commits to remote repository.
  `$ git push "remote" "branch name"`

### Branches

- List all local branches of the repo.
  `$ git branch`
- you can to create a new braunch named branch_name.
  `$ git branch "Branch name"`
- Delete the branch named "branch_name".
  `$ git branch -d "Branch name"`
- Create and switch to the new branch.
  `$ git checkout -b "branch name"`
- Switch to the branch which already exist.
  `$ git checkout"branch name"`
- Merge the provided branch with the current working branch.
  `$ git marge "branch name"`
- _Abort the action_ if there are any conflicts.
  `$ git merge -abort`

### To observe your Repository.

- Dsiplay the state of the working directory and the stating area. (More informaticon)
  `$ git status`
- You can to get status in short form.
 `$ git status -s`
- Display changes between commits or between commit and saved files.
 `$ git diff`
-  Display commit logs and diff output each commit introduces.
 `$ git whatchanged`