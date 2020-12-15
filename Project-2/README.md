# Project 2 - Deploy a High-Availability Web App using CloudFormation:

## List of screenshots:

### Project Architecture:
* Udacity Project 2.jpeg -- > Architecture of the project

### CloudFormation Stacks:
* Udacity Project 2 stacks.jpg -- > stacks created from my account

### Servers Stack Outputs:
* Udacity Project 2 Outputs.jpg -- > screenshot of CloudFormation servers stack outputs

### Web Browser Access:
* Udacity Project 2 URL.jpg -- > screenshot of the working website


## List of CloudFormation Scripts:

### Stacks:
* network-stack.yml
* servers-stack.yml

### Parameter files:
* network-parameters.json
* server-parameters.json

### Batch scripts to run stacks:
* create.bat -- > to create stack
* update.bat -- > to update stack
* delete.bat -- > to delete stack

## Web Browser Access:

URL:	http://udacityproject2-webapp-lb-1583356175.us-west-2.elb.amazonaws.com


## Notes:
* Bastion Hosts are created in public subnets to provide access to servers in private subnets if needed
* I know that KeyName should be removed, I kept it so bastion hosts make sense
* URL output is added to provide nice http://URL
* I used AWS Parameter Store  for sensitive data

