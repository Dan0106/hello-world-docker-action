# hello-world-docker-action

Deploy a Jenkins server in your local environment to build a hello world project (CI/CD).

1)	Write a dockerfile to create a container to print hello world message and push the dockerfile to your github repo (You can create a demmy github repo if you don’t have one)

2)	Write a Jenkinsfile to build the Dockerfile file from github repo in each branch (e.g. Master, develop branch) and push the docker image to docker hub. (Note: Use multibranch pipeline & Jenkins job should get triggered automatically when there is change in dockerfile in github)
