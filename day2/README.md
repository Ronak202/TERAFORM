# Day 2 – Variables and tfvars

- Used variables for filename and message
- Created dev.tfvars and prod.tfvars
- Ran Terraform using different variable files

Commands:
terraform apply -var-file="dev.tfvars"
terraform apply -var-file="prod.tfvars"
