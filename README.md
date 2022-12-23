# Git-Useful-Command

### To change http authentication to ssh authentication 

$ git remote -v
origin  https://kazitoufiq@dev.azure.com/kazitoufiq/mlops/_git/DatabricksDevOps (fetch)
origin  https://kazitoufiq@dev.azure.com/kazitoufiq/mlops/_git/DatabricksDevOps (push)


 ##### get the SSH link from clone button

$ git remote set-url origin git@ssh.dev.azure.com:v3/kazitoufiq/mlops/DatabricksDevOps

$ git remote -v
origin  git@ssh.dev.azure.com:v3/kazitoufiq/mlops/DatabricksDevOps (fetch)
origin  git@ssh.dev.azure.com:v3/kazitoufiq/mlops/DatabricksDevOps (push)

