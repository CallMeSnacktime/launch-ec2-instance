# Launch-EC2-Instance
Basic website on AWS server

Table of Contents
Project Overview
Features
Getting Started
Usage


Project Overview:
This terraform project launches an EC2 instance that hosts a a webpage on the server.
The project is meant to be used in Amazon CodeBuild where it can be updated when new commits are made

Features
* CI/CD intergration
* Website Hosting

Getting Started
Terraform is the only tool needed on the user machine 
(https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

Installation
Due to the metadata provided in buildspec.yml, the only installation required is terraform on the user machine.

Configuration
* Project was completed using Terraform v1.5.2.
* The environment used was Amazon Linux 2 (amazonlinux2-x86_64standard:5.0)

Usage
Mainly for deomonstrating ability to how a website and the ability to update in real time using CI?/CD

Contributing
N/A

Acknowledgements
[Give credit to any external libraries, resources, or individuals who have inspired or contributed to your project.]

Contact
[Provide your contact information or a way for users to reach out to you if they have any questions or feedback.]
