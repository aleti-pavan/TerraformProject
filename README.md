# TerraformProject

How to Run:

1. Save files on the disk.
2. update the terraform.tfvars with required values. ( stack name, access key, secret key , db username and db password)
3. makes sure you have terraform in your system/server.
4. execute sequence of steps below.


Provisioning:

   i)    terraform validate   (makes sure you don't have any errors in the code)
   ii)   terraform init ( initialization )
   iii)  terraform plan -out "<name>"
   iv)   terraform apply "<name>"
   
   Now the magic, Login into your account and check you should have resources created...!!!
   
Deprovisioning:

i) terraform destroy - will remove all the resources provisioned with terraform apply.
