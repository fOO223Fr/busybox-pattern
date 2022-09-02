### Prerequisite

- Fresh Openshift cluster especially no previous installed argocd

### Steps to have busybox pattern running

Note this pattern doesn't use ACM, Vault. 

1. login to your cluster as cluster admin
2. Install Validated pattern ![operator](images/main/install.png?raw=true)
3. Create Pattern ![create](images/main/create.png?raw=true)
4. Fill-in the form with target-Repo being this ![repo]((images/main/create-1.png?raw=true))
5. Wait for few minutes check the status of the pattern you just created

The application is deployed in busybox-pattern namespace