Create the VPC using ansible. Make sure the code work in every region of AWS.  
==============================================================================
1. VPC 

2. 6 subnets 

   3 private  

   3 public  

4. Public subnets should have IGW attached to it.  

5. Private subnets should have NG attached to it.  


6. Configure route tables properly. Once private and public subnet created, please create ec2 instance (manually)
on public subnet and ping google.com. If everything is successful, you should have proper response 


Requirements
------------
In order to work with Python 2.7.16, install next packages:
* yum install ansible -y
* amazon-linux-extras install ansible2
* yum install python-boto3 -y
* yum install python-pip -y
*  pip install boto awscli





Issues 
=======
1)  This  issue you will get when the List of Elasti IPs will be 5. In order to solve the problem, delete one EIPs and run again.

<img width="954" alt="Screenshot_492" src="https://user-images.githubusercontent.com/13994900/80157006-e1e3b880-858a-11ea-8833-1b62cdc3e130.png">

2) To solve the next issue, use #map_public: yes , under each Public Subnet!
<img width="924" alt="Screenshot_491" src="https://user-images.githubusercontent.com/13994900/80157055-ffb11d80-858a-11ea-9e28-276768fd89b8.png">

<img width="244" alt="Screenshot_494" src="https://user-images.githubusercontent.com/13994900/80157606-2b80d300-858c-11ea-8a87-4f1b0ee8a178.png">
                              
 
Time spent on  project
===========================

<img width="350" alt="Screenshot_500" src="https://user-images.githubusercontent.com/13994900/80165896-2cbcfa80-85a2-11ea-84f7-408e7d78a54a.png">


<img width="350" alt="Screenshot_503" src="https://user-images.githubusercontent.com/13994900/80166268-23805d80-85a3-11ea-9996-496e46bb7cf5.png">
