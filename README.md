# ECE444-Lab-Week4&5: Docker Intro

To build a docker, first I added a `requirements.txt` file in my project so that I can install all the required packages in the container.    

Then, I included a `Dockerfile` including a list of commands for creating a docker image. The picture below shows the location of the `Dockerfile`:  
<img src="https://github.com/yitongknows/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/img/Screenshot_19.jpg" width="400"> 

Next, I added the `docker-compose.yml` file which allows me to run multiple docker containers by running the command `docker-compose up`.

Next, I ran the command `docker build -t lab4:latest .` to build the docker image. 

To run the docker, I used the command shown below:
<img src="https://github.com/yitongknows/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/img/lab4_3.jpg" width="900">  
This screenshot also shows the docker image for this project. 

Alternatively, I can run the command `docker-compose up` to build and run the container.

The following pictures shows the project is running inside the docker container:
* Screenshot of the project
<img src="https://github.com/yitongknows/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/img/lab4_1.jpg" width="700"> 
* Screenshot of the docker container
<img src="https://github.com/yitongknows/ECE444-F2020-Lab3/blob/lab4_Microservice_Experiment/img/lab4_2.jpg" width="1000">  


## Briefly summarize the differences between Docker and Virtual Machine.

Docker | Virtual Machine
------------ | -------------
 Docker has no operating systems, it runs the images and containers on host operating systems| each VM has its own operating system
 Docker requires fewer recources to run containers | VM requires more CPU cycles to run projects
provides isolated environments for each image | cannot guarantee the environment for different developers are the same for the project to run successfully  
takes a few seconds to run |takes longer time to start a VM 
Docker container can share hardware spaces between containers|requires more hardware space for multiple VMs
