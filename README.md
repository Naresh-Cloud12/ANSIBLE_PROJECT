# ANSIBLE_PROJECT
Provisioning + Configuration Management


Task - 1
task one will be to use anible control node where the control node will be our laptop which has anible installed already. using the anible that we have installed first task that we will do is provisioning...anible can be used for configuration management anible can be used for Network appliances 
step one we will be using anible for provisioning and where are we going to provision the resources we are going to provision on AWS AWS is a control plane AWS is a is platform so here you cannot connect anible with AWS using SSH... because it's not a server AWS is a IAM platform or the PaaS platform what you need to do you need to use ansible AWS collection and in the anible AWS collection you will have a module for ec2 we will be using that module and that module will be run on the control node so usual practice is that if you're using anible for configuration management you will connect to your manage node or the server and you will SSH to that machine and execute the anible module on that machine but here we are doing provisioning you cannot SSH to AWS so we will use connection type as local and we will run the module on the anible control node itself  
this module which is a python module using boto3 it will connect to the AWS API and it will provision the ec2 instances for us ----So this is the TASK 1

Task -2 

