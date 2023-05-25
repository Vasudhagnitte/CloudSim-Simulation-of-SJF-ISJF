# CloudSim-Simulation-of-SJF-ISJF
This is a CloudSim project ,comparing SJF and Improved SJF

This Code implementation is similar to the Conference paper published on the topic "An Improved SJF Scheduling Algorithm in Cloud Computing Environment.

Steps for the code implementation.

*First replace the code of DatacenterBroker.java(existing in the cloudSim)with the provided code of SJF or ISJF

*Note that, you can find DatacenterBroker.java class inside the package named as org.cloudbus.cloudsim in the cloudSim tool 

*Create a new class inside the package named as org.cloudbus.cloudsim.examples in cloudSim and name it as Simulation.java. Copy paste the Simulation.java code given to it.


After running both SJF and ISJF code, we can observe the following

*Makespan time as well as the average response time (higher configured VM) is reduced in Improved SJF

*The Cloudlets with longer length,have more tasks to execute,hence the cloudlets greater than the average length of cloudlets,is assigned with the higher VM's

In this Project we have considered the following:

*Number of Cloudlets:20

*Number of VM used:2

*Number of Datacenter:1

*Number of Hosts:1

You can also go through the text file on Explanation of Simulation.java code

For more knowledge and proper understanding of the concept, go through the conferance paper attached with this.


