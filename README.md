These are the jobs done in this project and successfully completed and output is got.

JOB#1
If Developer push to dev branch then Jenkins will fetch from dev and deploy on dev-docker environment.

JOB#2
If Developer push to master branch then Jenkins will fetch from master and deploy on master-docke environment.
both dev-docker and master-docker environment are on different docker containers.

JOB#3
Manually the QA team will check (test) for the website running in dev-docker environment. If it is running fine then Jenkins will merge the dev branch to master branch 

JOB#4
After the merging done, the dev1-docker environment should be destoyed automatically in order to save RAM/CPU resources

Here I have integrated Jenkins with Docker, Git (DCVCS) and GitHub (CVCS). Jenkins server is running in my RHEL 8 VM. I have described all the steps in my LinkedIn article. Please refer to my article to know more. Here is the 
https://www.linkedin.com/pulse/integration-git-github-jenkins-docker-sri-vishnuvardhan/?published=t
