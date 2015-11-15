## unifi-ec2-cloudformation
AWS CloudFormation template to deploy a Ubiquiti Unifi controller with Elastic IP and Security Group.
Use the AWS T2 instance type with a 30GB general purpose SSD volume.


![CloudFormationTemplate](http://ph2.us/github/unifi-ec2-cloudformation/aws-unifi-cf-designer.png)

## Usage
Download the JSON template, or clone the git repo...

``` script
git clone https://github.com/philliphenslee/unifi-ec2-cloudformation.git
```
   
   
   
   
From AWS CloudFormation, click "Create Stack" and then load the template file.
  
  

Enter the stack name and parameters, click next and then create. 


![UnifiStack](http://ph2.us/github/unifi-ec2-cloudformation/aws-unifi-parameters.png)

    
    
    
    
Take a short break while CloudFormation creates the new stack...

![UnifiInstance](http://ph2.us/github/unifi-ec2-cloudformation/aws-unifi-instance.png)
  
  
  
  
Configure the new Unifi Controller...

![UnifiSetup](http://ph2.us/github/unifi-ec2-cloudformation/aws-unifi-setup.png)







