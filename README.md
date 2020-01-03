# CloudFormation-Templates


**TASK 1**

Design a template to add a tag ‘bastion’ with the value set as ‘true’ to an EC2 instance, only if the Environment is ‘prod’ and Task is ‘bastion’. The values for the Environment and Task are retrieved from Parameters defined in the same template.


**TASK 2**

Design a template to create an RDS instance and retrieve the DB Password dynamically in the template, from the Systems Manager Parameter store. The Systems Manager Parameter store should have this parameter as a SecureString
