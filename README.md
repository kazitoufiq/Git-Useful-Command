# Git-Useful-Command

## To change http authentication to ssh authentication 

##### First check the remote link 

$ git remote -v

origin  https://kazitoufiq@dev.azure.com/kazitoufiq/mlops/_git/DatabricksDevOps (fetch)

origin  https://kazitoufiq@dev.azure.com/kazitoufiq/mlops/_git/DatabricksDevOps (push)


##### Get the SSH link from clone button and set 

$ git remote set-url origin git@ssh.dev.azure.com:v3/kazitoufiq/mlops/DatabricksDevOps

$ git remote -v

origin  git@ssh.dev.azure.com:v3/kazitoufiq/mlops/DatabricksDevOps (fetch)

origin  git@ssh.dev.azure.com:v3/kazitoufiq/mlops/DatabricksDevOps (push)


#####
git clone https://xxxxdud@b/kaziwadud/budget_data_migration.git

git config --global user.name "Kazi Toufiq Wadud"

git config --global user.email "kazi.wadud@email.com"

git add . && git commit -m "initial commit"

git push origin main


Difference between clone  & pull :

	- clone - at the very beginning  (full entire repo)
	- Pull - only latest changes that local repo doesn't have

git clean -f  (remove everything in working directory)   - won't touch anything in staging
git rm <filename>
git log
	
### HOW TO CUT A NEW BRANCH

git branch
git checkout -b dev   (-b for create a new branch) 
	
### To see all the remote + local branches 
git branch -a
git branch -r
gitk --all
gitk --remotes

git branch <branch-name> origin/<branch-name>


