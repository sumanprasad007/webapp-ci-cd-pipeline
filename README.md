## DevOps Project for Beginners   

[![Image](https://github.com/yankils/Simple-DevOps-Project/blob/master/Devops_course.PNG "DevOps Project - CI/CD with Jenkins Ansible Docker Kubernetes ")]



cd /opt/Docker;
docker build  -t nfliximage .;
docker stop  nflixapp;
docker rm  nflixapp;
docker run -d --name  nflixapp -p 8088:8080 nfliximage
