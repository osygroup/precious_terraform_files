# precious_terraform_files

## Part I: Deliver Terraform Code

The directory _terraform_blobstorage_ contains the main.tf and variables.tf files used to create the Azure Storage Account and Storage Container. These resources were used to create a Helm repository needed for Part II of the assessment.


## Part III Setup an AKS cluster and Azure SQL Database 

The directory _terraform_aks_ contains the main.tf and variables.tf files used to create the AKS cluster running on two nodes and deployed into a new Azure Virtual Network. The Helm chart created for Part II of the assessment was deployed in this cluster.

The terraform files for the Azure SQL Database ensure a more secure terraform script in which the admin_password protection for the Database Server is hidden.

Use "terraform output -json" to view the admin_password and other output vaules after applying the terraform script.
