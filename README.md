### Give your Application Auto-Deploy Superpowers
<br>
This repository contains solution to the project "Give Your Application Auto-Deploy Superpowers" 
<p align="left">
A CI-CD pipeline for a client/server TypeScript project with backend hosted on AWS EC2 and frontend on AWS S3 bucket and served via CloudFront, monitored with Prometheus with Slack used for alerts. AWS Infrastructure created with Cloud Formation Templates, Ansible used in server configuration and Prometheus configuration </p>

<p align="center">
<small><i>the fictional "UdaPeople" Product is a (Cloud-Based Software) Product,  a revolutionary concept in Human Resources which promises to help small businesses care better for their most valuable resource: their people."</i></small>
</p>

## Understanding CI/CD and its Business benefits.

■	As we know, technology plays a crucial role in driving business growth and competitiveness. it's essential to stay up-to-date with the latest tools and practices. One such practice is Continuous Integration and Continuous Deployment (CI/CD).

■	CI/CD (Continuous Integration/Continuous Deployment) is a software development practice that helps teams automate the building, testing, and deployment of software.

■	Continuous Integration (CI) is the process of automatically compiling and testing code changes as they are made by developers. Every time a developer checks in their code to a shared repository, the CI tool automatically builds the application and runs tests to ensure that the code changes do not break any existing functionality. This helps to catch issues early in the development process, reducing the risk of bugs and errors creeping into the software.

■	Continuous Deployment (CD) is the process of automatically deploying new code changes to production environments. Once the code has been built and tested by the CI system, it can be automatically deployed to the cloud-based infrastructure where the application is hosted. This process ensures that the most up-to-date version of the software is always running in production, without any manual intervention needed.

![image](https://user-images.githubusercontent.com/99427790/223754928-ba2d8dd2-5e1f-4346-abf2-bf3e54a59222.png)



### Business benefits of implementing CI/CD pipeline in organization

![image](https://user-images.githubusercontent.com/99427790/223755213-2231e79d-f1a7-4c59-8eeb-b1124edd4c98.png)




### This App is Built With

- [Circle CI](www.circleci.com) - Cloud-based CI/CD service
- [Amazon AWS](https://aws.amazon.com/) - Cloud services
- [AWS CLI](https://aws.amazon.com/cli/) - Command-line tool for AWS
- [CloudFormation](https://aws.amazon.com/cloudformation/) - Infrastrcuture as code
- [Ansible](https://www.ansible.com/) - Configuration management tool
- [Prometheus](https://prometheus.io/) - Monitoring tool




## Prerequisites

* [Nodejs 13](https://nodejs.org/en/)
* [Docker](https://www.docker.com/)
* [GitHub account](https://github.com/)
* [CircleCi account](https://circleci.com/)
* [AWS account](https://aws.amazon.com/)
* [kvdb api bucket](https://kvdb.io/)
* [Slack api App and Workspace](https://slack.com/)



## Project Pipeline
![image](https://user-images.githubusercontent.com/99427790/224472459-7c94be40-9737-4871-b68b-f93e2216ba59.png)



## Project files
Relevant project files

* [Frontend Folder](./frontend/) : Contains the frontend files of the application, access the [README](./frontend/README.md) on how to use locally

* [Backend Folder](./backend/) : Contains the backend files of the application, access the [README](./backend/README.md) on how to use locally

* [Circleci Folder](.circleci): Contains the circleci [config file](.circleci/config.yml) for the CI/CD pipeline as well as the [ansible folder](.circleci/ansible/) with the different playbooks for server configuration. The [files folder](.circleci/files/) contains the cloud formation templates for AWS infrastructure provisioning.



## Project Submission  
![image](https://user-images.githubusercontent.com/99427790/224472559-7e881341-5523-48c0-849f-2b9170478530.png)
