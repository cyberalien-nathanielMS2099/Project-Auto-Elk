Automated ELK Stack Deployment

The files in this repository were used to configure the network depicted below.
![Screenshot 2021-11-01 152105 diagram color revised](https://user-images.githubusercontent.com/83778250/139910089-920a3bc0-50b9-468e-a3a7-0c9ebd6793bb.png)
These files have been tested and used to generate a live ELK deployment on Azure. They can be used to either recreate the entire deployment pictured above. Alternatively, select portions of the Playbook  file may be used to install only certain pieces of it, such as Filebeat.

The .yml file
This document contains the following details:
Description of the Topologu
Access Policies
ELK Configuration
Beats in Use
Machines Being Monitored
How to Use the Ansible Build
Description of the Topology.

The main purpose of this network is to expose a load-balanced and monitored instance of DVWA, the D*mn Vulnerable Web Application.
Load balancing ensures that the application will be highly Available, in addition to restricting Access to the network.
Load balancing routes the incoming traffic to make sure there is always A wed-server is available . 
The advantages of a jump box is it allows easy administration  to systems and provides extra security.
Integrating an ELK server allows users to easily monitor the vulnerable VMs for changes to the events log and system metrics.
Filebeat watches specific log directories and files, it collects data and then saves it.
Metricbeat gathers  data and stats and sends them to be stored in a logstash. The  data can be seen in apps like Kibana.
The configuration details of each machine may be found below. 

Name
Function
IP Address
Operating System


![Screenshot 2021-11-01 144614 jpj1](https://user-images.githubusercontent.com/83778250/139910268-03ed4bf1-599c-44cd-9679-de4acb4a51f2.png)


Access Policies
The machines on the internal network are not exposed to the public Internet.
Only the Jump-Box-Provisioner  machine can accept connections from the Internet. Access to this machine is only allowed from the following IP addresses: John's and personal IP address
My person ip address, 47.224.143.241

Machines within the network can only be accessed by  Jump-Box-Provisioner.
Only the Jump-Box-Provisioner can access the Elk-stack through SSH. 
What was its IP address?  10.1.0.4
A summary of the access policies in place can be found in the table below.

![Screenshot 2021-11-02 092654 jpg2](https://user-images.githubusercontent.com/83778250/139906098-8849ad5a-cc47-486f-9a18-7292ad5ccd77.png)


