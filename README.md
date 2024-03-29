# Terraform-AWS

## Introduction
This repository contains a Terraform configuration that can be used to create a development environment in AWS. The environment includes a virtual machine, a network, and a storage account.

## Requirements
To use this repository, you will need the following:

* A Terraform installation
* An AWS account
* An SSH key

## Usage
To create the development environment, run the following command:
```
cd Terraform-AWS-Dev-Environment
terraform init
terraform apply
```

This will create the following resources:

* A virtual machine
* A network
* A storage account

The virtual machine will be configured with the following:

* A Linux operating system
* The necessary tools for development

The network will be configured with the following:

* A public IP address
* A private IP address

The storage account will be configured with the following:

* A container for storing development artifacts

## Troubleshooting
If you encounter any problems, please see the following troubleshooting tips:

* Make sure that you have the correct version of Terraform installed.
* Make sure that you have an AWS account and that you have configured your environment variables.
* Check the output of the terraform plan command to see if there are any errors.
