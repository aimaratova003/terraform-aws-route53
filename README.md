# terraform-aws-route53

```
module "terraform_elb" {
  source ="aimaratova003/terraform-aws-route53/aws"
  instance_type = var.instance_type
  ami = var.ami
  key_name = "aigerim1"
}
