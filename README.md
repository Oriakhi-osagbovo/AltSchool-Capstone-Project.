# AltSchool-Capstone-Project.

## Project Tasks

- Everything will be deployed using an Infrastructure as Code approach
- In your solution please emphasize readability, maintainability and DevOps methodologies. We expect a clear way to recreate your setup and will evaluate the
  project decisions on:  
  · Deploy pipeline  
  · Metrics  
  · Monitoring  
  · Logging  
  · Use Prometheus as a monitoring tool  
  · Use Ansible or Terraform as the configuration management tool  
  · You can use an IaaS provider of your choice.  
  · The application should run on Kubernetes

---

## Steps to recreate

- Create a circleCI account
- Get an AWS account and create a programmatic user with adminstratoraccess and save the access key and secret access key as environment variable on circleCI
- Create a dockerhub account with user as DOCKERHUB_USER and password as DOCKERHUB_PASSWORD and save this as environment variable in your circleCI account
- Setup the project repo in circleCI account
- Replace the domain name in the "./terraform/variables.tf" file
- Run the pipeline
