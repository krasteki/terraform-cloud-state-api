# Learn Terraform Cloud State API

This is a companion repository for the [Learn Terraform Cloud State Versioning tutorial](https://learn.hashicorp.com/tutorials/terraform/tfc-state-api) on HashiCorp Learn. Follow along to learn more about state management.




The main resources in this configuration are an AWS EC2 instance and a security group with port 8080 access.

I. Create infrastructure 

1. Clone the repo
```
$ git clone https://github.com/krasteki/terraform-cloud-state-api.git
```

2. Enter in the cloned directory
```
$ cd terraform-cloud-state-api
```

3. Update your configuration with your Terraform Cloud information. Update <YOUR-ORGANIZATION-NAME> with your Terraform Cloud organization name.

4. Authorize to terraform cloud

```
$ terraform login
```

5. Add AWS cred to workspace variables
6. `terraform init` and `terraform apply`