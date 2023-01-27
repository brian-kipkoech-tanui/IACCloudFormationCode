### Load Balancer Link [ALB](http://udape-webap-18jg48nh95s0o-1117866257.us-west-2.elb.amazonaws.com/)
### Project Title - Deploy a high-availability web app using CloudFormation
This folder provides the code for the "C2- Infrastructure as Code - Deploy a high-availability web app using CloudFormation" project. Note that the Key Pairs have been deleted from the account for security reasons.
The CloudFormation Code implements the following Architecture Diagram:
![Architecture Diagram](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/Architecturediagram.jpg?raw=true "Architecture Diagram")

This folder contains the following files:


#### final-project-starter.yml
This CloudFormation template contains code that provisions the networking resources and servers.
The screenshots below show the provisioned resources:

- CloudFormation Stack
![CloudFormationStack](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/CloudFormation%20Stack.png?raw=true "CloudFormationStack")

- CloudFormation Template
![CloudFormationTemplate](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/CloudFormation%20Template.png?raw=true "CloudFormationTemplate")

- CloudFormation Resources
![CloudFormationResources](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/CloudFormation%20Resources.png?raw=true "CloudFormationResources")

- CloudFormation Parameters
![CloudFormationParameters](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/CloudFormation%20Parameters.png?raw=true "CloudFormationParameters")

- CloudFormation Outputs
![CloudFormationResources](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/CloudFormation%20Outputs.png?raw=true "CloudFormationOutputs")

- CloudFormation Events
![CloudFormationEvents](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/CloudFormation%20Events.png?raw=true "CloudFormationEvents")

VPC

![VPC](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/VPC.png?raw=true "VPC")
![Subnets](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/Subnets.png?raw=true "Subnets")

Launch Configuration

![Launch Configuration](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/Launch%20configuration.png?raw=true "Launch Configuration")

Autoscaling Group

![Autoscaling Group](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/Autoscaling%20group.png?raw=true "Autoscaling Group")

Target Health

![Target Health](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/health%20status.png?raw=true "Target Health")

Load Balancer

![Load Balancer](https://github.com/brian-kipkoech-tanui/InfrastructureascodeCloudFormationProject/blob/master/Screenshots/Load%20Balancer.png?raw=true "Load Balancer")

#### server-parameters.json
I used a JSON file to increasing the generic nature of the YAML code. For example, the JSON file contains a "ParameterKey" as "EnvironmentName" and "ParameterValue" as "UdacityProject". 

In YAML code, the `${EnvironmentName}` would be substituted with `UdacityProject` accordingly.