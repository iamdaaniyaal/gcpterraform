# gcpterraform
Automation on Google Cloud Platform (GCP) using Terraform

## Running the Project

  1)Clone / Download the project.
  


  2)Change the GCP project id in ```main.tf``` to the GCP project id.

  3)Add the ```credentials.json ``` file to the working directory. This the service account key used by Terraform to run.

  4)Change ```storage_bucket_name``` in ```terraform.tfvars``` to a globally unique name.

  5)Change ```sql_database_instance_name``` in ```terraform.tfvars``` to a CloudSQL instance name which is not used in the project for one week.

  
