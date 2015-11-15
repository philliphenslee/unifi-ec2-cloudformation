## unifi-ec2-cloudformation
AWS CloudFormation template to deploy a Ubiquiti Unifi controller with Elastic IP and Security Group.
Using Ubuntu 14.04 LTS AMI, AWS T2 instance type and a 30GB general purpose SSD volume.


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
  
  
  
  
Configure the new Unifi Controller, and modify the security group as needed. 

![UnifiSetup](http://ph2.us/github/unifi-ec2-cloudformation/aws-unifi-setup.png)


## License
MIT Copyright © [Phillip J. Henslee II](https://github.com/philliphenslee/smartslack/blob/master/LICENSE)







