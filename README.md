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

