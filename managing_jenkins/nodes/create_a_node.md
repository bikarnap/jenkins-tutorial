# Create a node
There is also a [YouTube](https://youtu.be/I6Sb1ndxtOc "YouTube") video tutorial on creating a Linux node in Jenkins.

There is another [YouTube](https://youtu.be/meXR-DpO_Kk "YouTube") video tutorial on creating a Jenkins agene as a service on a Linux node.

A node can be created from the Jenkins browser UI.

Navigate to the nodes page Manage Jenkins > Nodes and Clouds.

Click on the _+ New Node_ button. This takes us to the page where we can provide a name to our node as shown in Picture. We also need to select the type of node. Select the type and click on the _Create_ button. When there is no any other nodes created, the type available is only Permanent. Whenever there is at least one node created, an additional type, Copy from, is also visible. This type enables us to copy the node configuration from another node.

![Picture. Jenkins new node creation](../screenshots/jenkins_new_node.jpg "Jenkins new node creation")

After this we will be navigated to the Node configuration page. A screenshot of the configuration page is shown in Picture.

![Picture. Screenshot showing Jenkins node configuration](../screenshots/jenkins_node_config_screenshot.jpg "Jenkins node configuration screenshot")

In the configuration page, the most important thing to enter is the remote directory where all the Jenkins job related directories and files are created during the execution of the job. In other words, the remote directory contains the workspace of a job. It is common to enter the remote directory as /var/jenkins for Linux nodes and C:\jenkins for Windows nodes. Let's say we are creating a Linux node, then in the Remote root diretory enter /var/jenkins. There is also a Number of executors field which is 1 by default. We will leave this as well as all other fields with their default values.

At the end, click on the _Save_ button. This will take us to the newly created node page, which has information related to bringing the node oneline. However, if it shows something similar as shown in Picture, we need to configure the JNLP port in the Security page
and setup the port. Click on the link that is provided, which will navigate to the Security page. In that page there is a section called Agents. Under Agents > TCP port for inbound agents, the option disabled is selected. Select Fixed option and give a port number such as 9009 and click on the _Save_ button. The option Random option can also be chosen, if you want the system to randomly choose a port.

![Picture. Screenshot showing JNLP port not configured](../screenshots/jenkins_node_jnlp_port_error.jpg "Jenkins node configuration screenshot")


# Next
Next we will look into Pipelines  in Jenkins. The following links have materials related to Pipelines.
1. [Pipeline in Jenkins](../../pipeline/Pipeline.md "Pipeline in Jenkins")
2. [Pipeline Key Concepts](../../pipeline/Pipeline_Key_Concepts.md "Pipeline Key Concepts")
3. [Piepline Types - Declarative and Scripted](../../pipeline/Declarative_vs_Scripted_Pipeline.md "Pipeline Types - Declarative and Scripted")

There is also a [YouTube](https://youtu.be/UFctZKYxypc "YouTube") video tutorial on creating a Pipeline.


