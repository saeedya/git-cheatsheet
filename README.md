# Git-cheatsheet

"Start a project"

  git --version : check your git version

  git init: Create new repository

  git clone <local-repo>: Clone local repository

  git clone <remote-repo>: Clone remote repository
 
"Adding files to staging area(index)"
  
  git add <filename>: Add single file
  
  git add . : Add all files
  
"Commit and sync"
  
  git commit -m "message": Commit all staged changes with informative message
  
  git commit --amend -m "New commit message": Modify commit message
  
  git remote add origin <remote-server name>: Connect local to remote repository
  
  git pull: Update local repository with remote changes
  
  git push origin master: Push changes to remote
  
"Branches"
  
  git branch <New-branch-name>: Create a new branch but stay on existing branch
  
  git checkout -b <New-branch-name>: Create a new branch ten switch to it
  
  git checkout <other-branch-name>: Switching branches

  git branch -d <branch-name>: Delete Branch
  
  git push origin <branch-name>: Push branch to remote
  
"Merge"
  
  git merge <branch-to-merge-into>: Integrates to another branch(e.g "Master")
  
  git diff <source-branch> <target-branch>: View changes between two branches
  
"Common workflow commands"
  
  git status: Overview since last commit
  
  git log: List all saved commits
  



