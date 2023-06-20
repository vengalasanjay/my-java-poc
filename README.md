## Prerequisites qwerty
- JDK 1.8 or later
- Maven 3 or later
- MySQL 5.6 or later
######
## Technologies 
- Spring MVC
- Spring Security
- Spring Data JPA
- Maven
- JSP
- MySQL
## Database
Here,we used Mysql DB 
MSQL DB Installation Steps for Linux ubuntu 14.04:
- $ sudo apt-get update
- $ sudo apt-get install mysql-server

Then look for the file :
- /src/main/resources/accountsdb
- accountsdb.sql file is a mysql dump file.we have to import this dump to mysql db server
- > mysql -u <user_name> -p accounts < accountsdb.sql
---------------------------------------------------------------------

##Project Title
Java Application Deployment with Terraform, Ansible, Docker, Kubernetes, and Jenkins

##Description
This project demonstrates the deployment of a Java application into a Kubernetes cluster using a combination of infrastructure provisioning with Terraform, configuration management with Ansible, containerization with Docker, and CI/CD pipeline automation with Jenkins.

ansible/: Contains Ansible playbook and inventory files for configuring the Kubernetes cluster.
docker/: Includes Dockerfile for building the container image and the Java application JAR file.
kubernetes/: Holds the Kubernetes deployment and service YAML files.
terraform/: Contains the Terraform configuration files for provisioning the necessary infrastructure resources.
Jenkinsfile: Defines the Jenkins pipeline script for automating the CI/CD process.

##Usage
1.Clone the repository:

2.Update the necessary variables and configuration files as per your environment and application requirements.

3.Provision the infrastructure resources using Terraform.

4.Configure the Kubernetes cluster using Ansible.

5.Build the Docker image and push it to a container registry.

6.Set up the Jenkins pipeline:

Create a Jenkins pipeline job and configure the necessary settings.
Set up the appropriate Jenkins credentials for accessing the Docker registry and Kubernetes cluster.
Copy the contents of Jenkinsfile into the Jenkins pipeline script section..

7.Trigger the Jenkins pipeline to automate the build, test, and deployment process.



