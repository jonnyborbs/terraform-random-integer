# terraform-random-integer
Create a random integer in HashiCorp Terraform.

This configuration requires no providers and uses only native functions in Terraform.

To adjust the length of the integer, adjust the `min` and `max` values in `main.tf`

The function returns a single output of `integer` and requires no inputs.

For more information on how to link this configuration to a Terraform Cloud workspace, see this blog post:
https://www.hashicorp.com/blog/using-terraform-cloud-and-version-control-systems/
