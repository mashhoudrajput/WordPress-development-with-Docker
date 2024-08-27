# WordPress Development with Docker

This repository contains a Docker Compose setup for running WordPress with a MySQL database in a local development environment.

## Prerequisites

- Docker installed on your system
- Docker Compose installed

## Setup Instructions

1. **Clone the repository:**
   git clone https://github.com/mashhoudrajput/WordPress-development-with-Docker.git
   cd WordPress-development-with-Docker

2. **Start the services:**
   docker-compose up -d

3. **Access WordPress:**
   - Open your browser and navigate to http://localhost:8000

## Customization

Modify docker-compose.yml to change environment variables, port mappings, and volumes as needed.

## Stopping the Containers

To stop and remove the containers, run:
docker-compose down

## License

This project is licensed under the MIT License.
