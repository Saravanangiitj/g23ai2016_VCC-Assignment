# g23ai2016_VCC-Assignment
This is assignment is part of Virtualization and cloud computing Student Name - Saravanan Gnanapandithamani(G23AI2016)
Assignment Requirment: Create a Docker image of Web Application and Deploy and Run inside the container

Below are the options to build container applications

- Build the project and later containerize it
- Build the project inside the the container
To run the container, follow these steps:
Building the Docker Image:
docker build -t mybuild -f dockerfile .
Running the Container:
docker run -it --name mypro -p 80:80 mybuild
After getting inside the container Input the command:
service apache2 start
After which open the browser and type below command in the browser:
localhost/myproject/
Installed Packages Git/Apache2/Net-tools
For troubleshooting, below commands can be used,
docker images
docker ps
docker ps -a
or after login into the container into the bash :
service apache2 status
