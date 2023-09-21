# git-work-flow

## best scenario
1. A person will create a repository on Github
    - with 2 branches: Master & Dev
    - Master is production branch -- never touch this branch
    - To develope new feature, create new branch call feature/:feature-name
2. Leader assigns tasks for his team mates
    - task will be assigned in 'Issues' tab
    - each task will have an id with symbol #
3. Developing new feature
    - developer create new branch from Dev branch
    - remember to commit with symbol # and issue Id to address task is done for specific issue
    - push codes to create pull request 
4. Review code
    - merge feature branch to dev branch after review
5. Realease
    - create a realease branch with version number
    - create a tag with version number
    - merge dev branch to realease branch
6. Push to production
    - merge to Master branch when everything is ready
7. Hotfixes
    - in case bugs in production code, create hotfix branch
    - fix code and commit with issue id
    - merge back to Master or Dev to further fix
    
