# Job in Jenkins
A job in Jenkins can be anything from a simple printing a string of text to a complete software development job that includes diffrent steps such as build, test, and deploy, among others. In this section, we will look into a simple job in Jenkins. We will create a job in jenkins, a freestyle job, that will run in the Built-in node. Built-in node is the machine where Jenkins controller itself is running.

## Create a new job in Jenkins
In order to create a new Jenkins job, click on the *+ New item* button on the Jenkins home page (Dashboard page). In the screen that appears, give your job a name and select Freestyle job. An example is shown in Picutre 1.

![Freestyle Job Creation](../pictures/create_a_freestyle_project.jpg "Freestyle Job Creation")
*Picture 1: Creating a freestyle job in jenkins*

Then click on the *OK* button. This will create a new Freestyle job with the given name. You will be taken to the job configuration page after you click the *OK* button. The configuration page is the place where all the things that the job needs and does are configured. For example, Picture 2 shows a Job configuration page.

![Job Configuration page](../pictures/jenkins_job_configuration.jpg "Job Configuration page")
*Picture 2: Job configuration page screenshot showing part of the configuration*

It can be seen from Picture 2 above, that the job configuration page has multiple configuration menus such as _General_, _Source Code Management_, and _Build Triggers_, among others. Each of the menus can be used to configure specific things. However, the most important menu is _Build steps_ where the things that the job needs to do are configured. For this part, we will keep our job simple. In the _Build Steps_ section of the Job configuration, click on the _Add build step_ button, and select _Execute shell_ (select _Execute Windows batch command_ if Jenkins is installed on a Windows machine). An example build step is shown in Picture 3. This example will be our first Jenkins job.

![Jenkins simple job](../pictures/jenkins_job_configuration_build_steps_execute_shell.jpg "Jenkins simple job")
*Picture 3: A simple Jenkins job build step that will execute command on a linux shell*

The build step from the example shown in Picture 3 above executes simple shell commands on a linux machine. The linux machine in this case is the Built-in node. We will save the configuration by clicking on the _Save_ button at the bottom of the configuration page.

## Build a job
After we have a job created and configured, we are ready to build that job. Building of a job is really simple. The job page has a menu on the left side named _Build now_, which when clicked starts building the job.