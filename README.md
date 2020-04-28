# Docker-Project
Project build on top of docker. It launches a E-Commerce Website for essential items in just one second.
Title: Online E-Commerce Website for supplying essential items needed during this lockdown
@author: Muhammad Tabish
@github: https://github.com/mtabishk
@LinkedIN : https://www.linkedin.com/in/mtabishk/

This is a project build on top of docker aimed at supplying essential items like Masks, Gloves, Sanitizers, Body suits and any other essential item needed during this times of Coronavirus .
In this project 3 containers are launched 2 of which are Wordpress running on port 8080 and 8081 both linked by PAT to manage a load of customers,  used hosting  for website . The other container is for storing the essential information about the customers and the goods they buy.

The most important thing is to save data permanently stored in those containers in case the containers are crashed , for that I have mounted storage in docker for supporting this isuue. 
Now you can fell free about your data , It will be never lost.

Also an amazing this about this project is that I have written all the code to build this project in a single docker compose yml file. I will help you to launch the project in 1 second
by only running a single command.

Requirements:
1.RedHat Linux 8 or Centos 8
2.Docker 
3.Docker Compose


This project has a docker-compose.yml file, which will start this project on your local machine and help you see changes instantly.

If you wish to run the project, you can use the following command:

docker-compose up

