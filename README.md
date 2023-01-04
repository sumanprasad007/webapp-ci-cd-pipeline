In this project, we will be setting up a CI/CD pipeline for a web application using Jenkins and Tomcat servers. Jenkins is a popular open source automation server that helps to automate parts of the development process. It can be used to build, test, and deploy software projects automatically. Tomcat is an open source web server and servlet container that is used to deploy Java-based web applications. We will be hosting both Jenkins and Tomcat on AWS Cloud EC2 instances. EC2, or Elastic Compute Cloud, is a scalable cloud computing service provided by AWS that allows users to launch and manage virtual servers in the cloud. By hosting our servers on EC2, we can take advantage of the scalability, security, and reliability of the AWS infrastructure. The flow of the project will involve the Jenkins server pulling the source code from GitHub and then triggering jobs to build and deploy the application to the Tomcat server. GitHub is a popular version control platform that allows developers to collaborate on code and track changes. By integrating Jenkins with GitHub, we can automate the process of pulling the latest code changes and triggering a build and deployment process whenever new code is pushed to the repository.

The advantage of using a CI/CD pipeline is that it allows us to automate the build, test, and deployment process, saving time and reducing the risk of errors. It also makes it easier to collaborate with team members, as code changes can be automatically built and deployed without the need for manual intervention. By setting up a CI/CD pipeline using Jenkins and Tomcat on AWS Cloud EC2, we can streamline the development process and ensure that our web application is consistently delivered to users in a reliable and efficient manner.

## DevOps Project for Beginners   

[![Image](https://github.com/yankils/Simple-DevOps-Project/blob/master/Devops_course.PNG "DevOps Project - CI/CD with Jenkins Ansible Docker Kubernetes ")]



cd /opt/Docker;
docker build  -t nfliximage .;
docker stop  nflixapp;
docker rm  nflixapp;
docker run -d --name  nflixapp -p 8088:8080 nfliximage
