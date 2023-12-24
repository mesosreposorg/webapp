# Project Title
This project is intended to touch and feel containerized Web Application

# Pre-Requisites
Step 1: Launch ec2 instance to run terraform with name sandbox

Login to sandbox instance

$sudo yum install git -y

$git clone https://github.com/cssporg/webapp.git

$cd webapp

$sh sandbox.sh

$source export.sh

Step 2: Build Custom AMI with Packer

https://github.com/cssporg/packer


# Source Cluster on us-east-1 region
https://github.com/mesosreposorg/webapp/blob/main/webapp-src.md


# Data Backup, set up monitoring
https://github.com/cssporg/dr


# Destination Cluster on us-west-2 region
https://github.com/cssporg/webapp-dst
