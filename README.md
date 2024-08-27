WordPress Development with Docker
This repository contains a Docker Compose setup for running WordPress with a MySQL database in a local development environment.

Prerequisites
Docker installed on your system
Docker Compose installed
Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/mashhoudrajput/WordPress-development-with-Docker.git
cd WordPress-development-with-Docker
Start the services:

bash
Copy code
docker-compose up -d
Access WordPress:

Open your browser and navigate to http://localhost:8000
Customization
Modify docker-compose.yml to change environment variables, port mappings, and volumes as needed.
Stopping the Containers
To stop and remove the containers, run:

bash
Copy code
docker-compose down
License
This project is licensed under the MIT License.

