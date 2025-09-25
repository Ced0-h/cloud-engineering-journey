# CloudFormation Deployment via AWS Console

## Overview
This markdown captures the key steps and insights from deploying AWS resources using CloudFormation through the AWS Management Console. It’s designed to be standalone and reusable across projects.

## Key Concepts
- Infrastructure as Code (IaC) using YAML
- Stack creation via AWS Console
- Template upload and validation
- Resource provisioning and monitoring

## Deployment Steps
1. Navigate to **CloudFormation** in the AWS Console
2. Click **Create Stack → With new resources (standard)**
3. Upload your `template.yaml`
4. Configure stack name and parameters
5. Review and acknowledge IAM capabilities (Ensure that permissions are granted)
6. Launch the stack and monitor events

## Lessons Learned
- Understanding the CFT format and the yaml using the AWS CFT documentation 
- Console validation catches YAML errors early
- Outputs are useful for chaining multiple resources
- Stack events help debug deployment issues

- Tags and parameters improve reusability

## Next Steps
- Modularize templates
- Add mappings and conditions
- Explore nested stacks and CI/CD integration

#progressing effectively.


















