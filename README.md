This repository holds the source code related to OCR and AI ML modules for QSRS application.
<br>
All Step functions module should replace with <AWSRegionId>:<AWSAccountID>: with their respective region and their AWS account id to make it work.
<br>
Terraform modules should retrieve the AWS Account related secret key and access key along with the respective AWS region to make it work and provision the software bill of materials.
<br>
VPC ID, Subnet IDs, Security Groups, sns topic ARN etc should get added in the terraform modules.
<br>
AHRQ Main bucket Name : qsrs-ocr-poc-dev
<br>
AHRQ CMS File Drop bucket Name : qsrs-ocr-poc-pdf-drop-location-dev
<br>
Docker file should update the topic arn with appropriate region and account id: <AWSRegionId>:<AWSAccountID>:
<br>
folder_path should get changed based on the files for the database scripts to run (DataInsertion.py and process_algorithm_status.py)
<br>
Terraform Module : "terraform.tfvars" has all the names defined for initial SBOM provisioning and can change the value based on the application needs.
<br>
Other terraform files (*.tf) may needs to get updated based on QSRS requirements on the naming convention.
