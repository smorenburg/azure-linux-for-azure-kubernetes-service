# Azure Linux for Azure Kubernetes Service

## Deploying the resources using Terraform

Set the variables.

```bash
export TF_VAR_app="azlx"
export TF_VAR_location="northeurope"
```

Change into the `terraform` directory.

```bash
cd terraform
```

Initialize Terraform.

```bash
terraform init
```

Deploy the resources.

```bash
terraform apply -auto-approve
```
