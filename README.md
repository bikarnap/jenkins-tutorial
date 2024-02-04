# Jenkins Tutorial

Jenkins (the Jenkins Project) is an open-source automation server that provides hundreds of plugins to support building, deploying, and automating any project. It is supported by a large and growing community of developers, testers, designers, and other people interested in continuous integration, continuous delivery, and modern software delivery practices.

Jenkins is built on top of Java Virtual Machine (JVM). Therefore, a Java Development kit needs to be installed for Jenkins to work.

Go through the following texts to learn about Jenkins and gain the beginner's level understanding and skill to start using Jenkins. There are also YouTube video tutorials available. You can find them at the end of this document under Video Tutorial Links. You can also directly go to the YouTube Jenkins Tutorial playlist from [here](https://www.youtube.com/watch?v=YVG1vaPAKak&list=PLH_WAPlxQAmFa4o3bqhoKvyXHUhWzRTjn&pp=gAQBiAQB "Jenkins playlist")

# Table of Contents

* [Installation and Setup](#installation-and-setup)
    * [Installing Jenkins](#installing-jenkins)
    * [Initial Setup](#initial-setup)
* [Accessing Jenkins Dashboard](#accessing-jenkins-dashboard)
* [Jobs](#jobs)
* [Jenkins Pipelines](#jenkins-pipelines)
* [Jenkins Distributed Builds](#jenkins-distributed-builds)
    * [Jenkins Agents](#jenkins-agents)
* [Administering Jenkins](#administering-jenkins)
* [Jenkins plugins](#jenkins-plugins)
* [Upgrade Jenkins](#upgrade-jenkins)
* [Video Tutorial Links](#video-tutorial-links)


# Installation and Setup

The materials related to this section are in the directory [installation_and_setup](https://github.com/bikarnap/jenkins-tutorial/tree/master/installation_and_setup "Installation and setup materials").

## Installing Jenkins

There is a brief instruction file for installing Jenkins on the Ubuntu/Debian platform. There is also a link to a YouTube video tutorial. After the installation is complete, the next step is the initial setup of Jenkins so that we can start using the Jenkins automation server. [Material Direct link](./installation_and_setup/Ubuntu_Debian.md "Ubuntu_Debian.md")

## Initial Setup

After completing the installation process of Jenkins, next we need to go through the initial setup process. It involves unlocking jenkins, adding plugins, creating the first admin user, and configuring the jenkins instance url. [Material Direct Link](./installation_and_setup/Initial_Setup.md "Initial_Setup.md")

# Accessing Jenkins Dashboard

This chapter provides an introduction to the Jenkins Dashboard and its user interface. Direct link to the material is [here](./using_jenkins/know_jenkins_dashboard.md "here")

# Jobs

This chapter has examples on jobs as well as each job example has link to its related YouTube video tutorial. The job example involves the following:
1. [Simple freestyle job](./jobs/firstJob.md "firstJob.md") 
2. [Freestyle job involving artifacts](./jobs/archieveArtifacts.md "arhieveArtifacts.md")
3. [Freestyle job involving Git and GitHub integration](./jobs/integrateGitAndGitHub.md)

# Jenkins pipelines

Get to know about Jenkins pipelines from [here](./pipeline/ "Pipelines")

# Jenkins Distributed builds

This chapter has materials related to Jenkins nodes and agents. In this chapter, you can learn about Jenkins node and agents. You will also learn to create Jenkins node(s). [Direct link here](./managing_jenkins/nodes/ "Jenkins Distributed builds")

## Jenkins agents

This subchapter provides files for creating jenkins agent as service in both Linux/Ubuntu and Windows platforms. In addition, there is also a file containing instruction on how to create a Jenkins agent on Linux node. [Direct link here](./agents/ "Jenkins agents")

# Administering Jenkins

This chapter provides information regarding Jenkins administration. This can be a starting point for the administrators of Jenkins or users with administrative rights. [Direct Link here](./managing_jenkins/administering_jenkins.md "administering_jenkins.md")

# Jenkins plugins

This chapter provides information and how-to instruction about plugins and its installation. [Direct link here](./managing_jenkins/plugins/ "Jenkins plugins")

# Upgrade Jenkins

This chapter basically provides a link to YouTube that has tutoria on upgrading Jenkins version 2.401.2 to 2.426.3. [Direct Link here](./managing_jenkins/upgrade_jenkins.md "upgrade_jenkins.md")

# Video Tutorial Links

* [Jenkins installation on Ubuntu/Debian](https://youtu.be/YVG1vaPAKak "Tutorial video on Jenkins installation on Ubuntu/Debian")
* [Initial Setup of Jenkins](https://youtu.be/dRprQhS0fdg "Tutorial video on initial setup of Jenkins")
* [Jenkins Dashboard and User interface](https://youtu.be/tllInX8dD4U "Jenkins Dashboard and User interface")
* [Jenkins Freestyle Job - Simple](https://www.youtube.com/watch?v=RcCUoDG_OC4 "Jenkins Freestyle Job - Simple")
* [Jenkins Freestyle Job - with Artifact](https://youtu.be/BkM8h3avN8M "Jenkins Freestyle Job - with Artifacts")
* [Jenkins Freestyle Job with SCM integration](https://youtu.be/GuR2tNVVhOc "Jenkins Freestyle Job with SCM integration")
* [Creating a Jenkins Linux Node](https://youtu.be/I6Sb1ndxtOc "Creating a Jenkins Linux Node")
* [Pipelines and Jenkinsfile](https://youtu.be/UFctZKYxypc "Pipelines and Jenkinsfile")
* [Create a Jenkins agent as a service on Linux node](https://youtu.be/meXR-DpO_Kk "Create a Jenkins agent as a service on Linux node")
* [Upgarde Jenkins](https://youtu.be/yjllMwQz5B4 "Upgrade Jenkins")
