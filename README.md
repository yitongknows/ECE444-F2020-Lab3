# ECE444-Lab-Week4&5: Docker Intro

To build a docker, first I added a `requirements.txt` file in my project so that I can install all the required packages in the container.    

Then, I included a `Dockerfile` including a list of commands for creating a docker image.     

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
 aa | the operating system inside of a VM is hard to maintain
  aa | Ectremely error prone
| cannot guarantee the environment for different developers are the same for the project to run successfully
