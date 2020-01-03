# CloudFormation-Templates


**TASK 1**

Design a template to add a tag ‘bastion’ with the value set as ‘true’ to an EC2 instance, only if the Environment is ‘prod’ and Task is ‘bastion’. The values for the Environment and Task are retrieved from Parameters defined in the same template.


**TASK 2**

Design a template to create an RDS instance and retrieve the DB Password dynamically in the template, from the Systems Manager Parameter store. The Systems Manager Parameter store should have this parameter as a SecureString


**TASK 3**


Design a template with an AutoScaling Group that can launch instances in all available AZs in a region. Make sure the AZs are dynamically retrieved so the customer can deploy them to any region and the template should work without any manual intervention. In addition to the ASG, the template must also launch a standalone EC2 bastion instance in one of the AZ
