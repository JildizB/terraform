HomeTask
Create 2 IAM roles per account:

I. DEV account

1. DeveloperAccessRole

a) Read permissions on all EC2 actions

b) Read permissions on EKS

c) Full access to S3

2. DevopsAccessRole

a) Full permissions

II. PROD account

1. DeveloperAccessRole

a) Read permissions on all EC2 actions

b) Read permissions on EKS

c) Read Access to S3

2. DevopsAccessRole

a) Full admin permissions in Prod except for secrets

b) Full permissions on EC2