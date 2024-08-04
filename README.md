# 🌟 CT519 Final Project

## Author: Jakkapan Attala 66130030
## Project Overview:
This project demonstrates the setup and configuration of a Docker Compose environment with Nginx as a reverse proxy, distributing requests to multiple web servers using a round-robin method.

## Project Structure:
- **nginx/**: Contains the Nginx configuration file for the reverse proxy setup.
- **web_1_myweb/**: Contains the HTML content for the first web server.
- **web_2_myresearch/**: Contains the HTML content for the second web server.
- **web_3_ct519/**: Contains the HTML content for the third web server.
  - **ct519/**: Specific content for the CT519 section.
- **docker-compose.yml**: Docker Compose configuration file for setting up the services.
- **README.md**: Documentation for the project.

## Setup Instructions:
1. **Clone the repository**:
   ```sh
   git clone https://github.com/Jakkapan-a/ct519-final-exam.git
   cd ct519-final-exam
