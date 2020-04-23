Create the VPC using ansible. Make sure the code work in every region of AWS.  
==============================================================================
1. VPC 

2. 6 subnets 

   3 private  

   3 public  

4. Public subnets should have IGW attached to it.  

5. Private subnets should have NG attached to it.  

* dfd

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
1)  The next issue you will get when the List of Elasti IPs will be 5. In order to solve the problem, delete one EIPs and run again.

#fistphoto

