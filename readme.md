# CRM Application  
### Description  
Full stack Customer Relations Manager (CRM) application built using django  

## Features:  
* ###   Add new user details
* ###  View and manage existing user details
* ###   Edit/update user details
* ###   Delete existing user details
Besides basic CRUD functionality, the app also provides for user authentication  

## Usage:  
### Run on local environment (without docker)  
> pip instal requirements.txt
> 
> python manage.py runserver

### Run on local environment (with docker)  
> docker-compose build
> 
> docker run <your_image_name>
> 
> docker-compose up

### Deploy on AWS EC2  
> clone the repository into EC2
> 
> sudo docker build -t your_app_name:your_app_tag -f Dockerfile
> 
> sudo docker run -d -p external_port_no:docker_port_number your-image-name
