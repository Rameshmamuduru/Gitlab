**What is GitLab:**
  it is an web based got repository managet/SCM similat to the github but with many more devops tools/techiquies like
  
      **1. Git Repositories**
      Store and manage your source code.      
      **2. CI/CD Pipelines**
      Automate build, test, and deployment.      
      **3. Issue Tracking**
      Create tasks, bugs, and manage project work.      
      **4. Merge Requests**
      Review and merge code changes.      
      **5. DevSecOps Tools**
      Security scanning, vulnerability management.      
      **6. Container Registry**
      Built-in Docker image registry.      
      **7. Monitoring & Analytics**
      See pipeline results, deployments, and activity.

steps :
    1. Create account in Gitlab
    2. And Create an Project (make note untill add ssh key it will not allow to take ssh)
    3. Install git for CLI
    4. Configure git using below commands

        a. git Config --global user.name
        b. git Config --global user.email  

  **How to push code to gitlab???**
1. create a folde for you project in local
2. and intialize the git using below command
         git init
3. create a file and try to get the status of git using below command
4.       git status
5. and follow below command to push code to guthub
6.       git add .
7.       git commit -m "commit message"
8.       git push -u origin master
