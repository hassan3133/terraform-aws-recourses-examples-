![Maintained by Hassan](https://img.shields.io/badge/maintained%20by-Hassan.com-blue)

# Terraform examples on AWS (Amazon Web Services)

Terraform is used to create, manage, and update infrastructure resources such as physical machines, VMs, network switches, containers, and more. Almost any infrastructure type can be represented as a resource in Terraform.

This repo contains [Terraform](https://www.terraform.io/) code examples on AWS (Amazon Web Services).


## Quick start

You must have an [AWS (Amazon Web Services)](http://aws.amazon.com/) account.

The code consists of Terraform examples using HashiCorp Configuration Language (HCL) on AWS (Amazon Web Services).

All the code is in the [code](/code) folder.

For instructions on running the code, please consult the README in each folder.

This is the list of examples:


* [01-one-webserver-with-vars](code/04-one-webserver-with-vars) - Terraform Web Server with vars: Example of how deploy a single web server on AWS (Amazon Web Services). The web server returns "Hello, World" for the URL `/` listening on port 8080, which is defined as a variable.
* [02-cluster-webserver](code/05-cluster-webserver) - Terraform Cluster Web Server: Example of how deploy a cluster of web servers on AWS (Amazon Web Services) using EC2 and Auto Scaling, as well as a load balancer using ELB. The cluster of web servers returns "Hello, World" for the URL `/`. The load balancer listens on port 80.
* [03-create-s3](code/06-create-s3) - Terraform Create S3: Example of how deploy the creation of a S3 bucket on AWS (Amazon Web Services).
* [04-terraform-state](code/07-terraform-state) - Terraform State: Example of how to store the information about what infrastructure has been created on AWS (Amazon Web Services).
* [05-module-example](code/09-module-example) - Terraform Module: Example that contains a module example of a Terraform file on AWS (Amazon Web Services). It shows how to develop (not duplicating code) web server clusters in different environments using a module.
* [06-multi-repo-example](code/10-multi-repo-example) - Terraform Muti Repo: Example that contains a multi repo example of a Terraform file on AWS (Amazon Web Services). It shows how to develop (not duplicating code) web server clusters in different environments using a module in another repo in order to use different version of the module in the environments.
* [07-loops-example](code/11-loops-example) - Terraform Loops: Example that contains the loops example of a Terraform file on AWS (Amazon Web Services).
* [08-zero-downtime-deployment](code/14-zero-downtime-deployment) - Terraform Zero-Downtime Deployment: Example that contains a zero-downtime deployment example of a Terraform file on AWS (Amazon Web Services).
