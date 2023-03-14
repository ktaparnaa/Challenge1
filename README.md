# Challenge1
#A 3-tier environment is a common setup. Use a tool of your choosing/familiarity create these resources on a cloud environment (Azure/AWS/GCP). Please remember we will #not be judged on the outcome but more focusing on the approach, style and reproducibility.

#

#YAML Files (Automated Process of creating Infrastructure using AWS Cloud  Formation Templates instead of manually) in the repo will create below resources for 3 Tier Architecture:

#VPC
#Route Table
#Internet Gateway
#Attaches Internet Gateway to the VPC 
#2 Public Subnets 
#Scaling Policy for Public Subnets
#Route Table for Public Subnets
#Associate the Public Subnets to the Route Table
#Security group with HTTP & SSH to open to 0.0.0.0/0
#Launch Template with Bootstrap script to install & launch Apache
#AutoScaling Group for Public Subnets
#Scaling Policy
#4 Private Subnets —  2 for Web Layer (Different Availability Zones : us-east1a & us-east1b) &  2 for Application Layer (Different Availability Zones : us-east1a & us-east1b)
#AutoScaling Group for two Private Subnets in the Application tier

