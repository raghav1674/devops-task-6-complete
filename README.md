# devopstask6

## TASK DESCRIPTION:




## 1. Create container image that’s has Jenkins installed using dockerfile Or You can use the Jenkins Server on RHEL 8/7

[Dockerfile](https://github.com/raghav1674/DEVOPS2/blob/master/Dockerfile)






## 2. When we launch this image, it should automatically starts Jenkins service in the container.



<img src="https://github.com/raghav1674/devopstask3/blob/master/DEVOPS-TASK-THREE/jenkins-runn.PNG" >



##  Job2 ( Seed Job ) : Pull  the Github repo automatically when some developers push repo to Github.
    Further on jobs should be pipeline using written code  using Groovy language by the developer
    
    
  [SEED_JOB](https://github.com/raghav1674/devops-task6-seed/blob/master/seed_job)


<img src="https://github.com/raghav1674/devops-task-6-complete/blob/master/job_generated_seed.PNG">


For running the DSL Script either you can approve in **In-process Script Approval** or u can disable **Enable script security for Job DSL scripts**   option in **MANAGE JENKINS > CONFIGURE GLOBAL SECURITY**

<img src="https://github.com/raghav1674/devops-task-6-complete/blob/master/diable_this.PNG ">

## 3. Create a job chain of job1, job2, job3 and job4 using build pipeline plugin in Jenkins
 Job1 : Pull the Github repo automatically when some developers push repo to Github.
 
 
 
 <img src="https://github.com/raghav1674/devopstask3/blob/master/DEVOPS-TASK-THREE/github-pull.PNG">
<img src="https://github.com/raghav1674/devopstask3/blob/master/DEVOPS-TASK-THREE/kubectl-all.PNG" >

 
 
 
## Job2 :
  1. By looking at the code or program file, Jenkins should automatically start the respective language interpreter installed image container to deploy code on top of Kubernetes ( eg. If code is of PHP, then Jenkins should start the container that has PHP already installed )
2. Expose your pod so that testing team could perform the testing on the pod
3. Make the data to remain persistent ( If server collects some data like logs, other user information )

[HTML_DEPLOYMENT_YAML_FILE](https://github.com/raghav1674/devopstask3/blob/master/create_html_deploy.yml)

[PHP_DEPLOYMENT_YAML_FILE](https://github.com/raghav1674/devopstask3/blob/master/create_php_site_deployment.yml)


## Job3 : Test your app if it is working or not.
## Job4 : if app is not working , then send email to developer with error messages and redeploy the application after code is being edited by the developer


<img src="https://github.com/raghav1674/devopstask3/blob/master/DEVOPS-TASK-THREE/mail.PNG" >


