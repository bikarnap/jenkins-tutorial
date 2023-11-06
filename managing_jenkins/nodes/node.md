# Jenkins Node
A Jenkins node is a physical machine or a virtual machine that can be used to run Jenkins jobs. We can create a Windows Jenkins node or a Linux Jenkins node. We need to follow few steps to setup a Jenkins node. Jenkins node has so called executors that execute jobs.When a Jenkins node is setup, the number of executors is also defined. For example, if a Jenkins node has two executors, two jobs can be executed in concurrently in that node.

When Jenkins is installed, it also creates a built-in node that has two executors by default. As the volume of jobs to be executed increase, the built-in node is not sufficient for which additional nodes are necessary. Built-in node can be used for example during learning to use Jenkins and running some jobs that are related to the Jenkins server itself. An example of a job that is related to the Jenkins server itself could be a backup job for backing up all the Jenkins configuration related to jobs. It is however discouraged to run jobs on the built-in node for security, performance, and scalability reasons.

A Jenkins node is nothing, but a machine that runs Jenkins build agent as a service. The build agent is a JAR file (agent.jar).

## Executors
As mentioned above, executors run multiple jobs concurrently. An executor is basically a slot for the execution of jobs. Effectively, it is a thred in the Jenkins agent. Determining the number of executors in a node depends on the amount of resources available in the node. Generally speaking, CPU and memory requirements are the basis on determining the number of executors. In addition, amount of I/O operations and network activity should also be considered while setting up the number of executors.

It is always possible to change the number of executors in a node. Monitoring the I/O performance, CPU load, memory usage, I/O throughput can help to determine the executors' status on a node. This in turn helps to figure out if the number of executors in the node needs to be decreased. Setting the number of executor to 0 means that no job will run in that node. The safest choice is always setting the number of executor to 1.

## Agents
Agents and nodes are essentially the same thing practically. However, these two are conceptually separate. The agents manage the execution of tasks on behalf of the Jenkins controller in the executors. These can run on any operating system that supports Java. These make it possible to install any tools that is required for build and test tasks.