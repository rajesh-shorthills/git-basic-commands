1. Clone git repo from Https url:
  git clone <Repo Https url>
  
2. To list all branch from local repo repo:
   git branch
   
3. To list all branch from remote Repo or Original Repo:
  git branch -a
  
4. Checkout or switch to a new branch:
  git checkout <branch-name>

5. Create a new branch from master:
  first of all checkout master branch. Then take pull. After then run following commands
  git branch -b <new-branch-name>
  
  After create new branch add some code and push the code. After that run following command
  git push -u origin <new-branch-name>

6. Delete a branch on your local filesystem :
    git branch -d <branch name>

7.To force the deletion of local branch on your filesystem :
  git branch -D <branch-name>
  
8. Delete the branch on github :
  git push origin : <branch name>
  
9. To update your repo with remote repo:
  git pull
  
10. To check status of branch:
  git status
