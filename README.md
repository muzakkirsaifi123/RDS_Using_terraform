## Create a RDS service using Terraform.

-------------

**Files:** 
```
    module.tf
    provider.tf
    resource.tf 
```

## Apply the terraform script

1. First configure the aws credentials using aws-cli with your profile name.

        aws configure --profile terraform

2. Now, from the current directory run the following command to validate the script.

        terraform validate
3. Now intialize the current working directory.

         terraform init
3. To check the plan for the terraform

        terraform plan

4. Applying the terraform script

        terraform apply -auto-approve
