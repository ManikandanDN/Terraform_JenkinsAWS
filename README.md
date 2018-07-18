# Terraform_JenkinsAWS

Terraform script to create Jenkins nodes on AWS
This will create two instances for you once as "Jenkins_Master" and another "Jenkins_Slave"

*# You will need to add creds.tf file with the following info added

provider "aws" {
    access_key = "YOUR_ACCESS_KEY"
    secret_key = "YOUR_SECRET_KEY"
    region = "ap-south-1"
}

Once done Just do
#terraform plan
#terraform apply
