# Bitlion Community Platform

## Overview

Bitlion Community is an open-source Governance, Risk, and Compliance (GRC) platform designed to help organizations manage compliance requirements efficiently and transparently.  
It supports various regulatory frameworks such as ISO standards, data privacy regulations, POJK, PBI, and other governance-related controls.

The platform is built to support data governance, risk management, compliance operations, and cybersecurity controls in a structured and auditable manner.

---

## Project Structure

This repository contains all required components to deploy the Bitlion Community platform using Docker.

### Main Files & Directories

- docker-compose.yml  
  Defines all required services:
  - Application service  
  - PostgreSQL database  
  - Redis service  
  - Nginx reverse proxy  

- nginx.conf  
  Nginx configuration for routing and serving the application.

- README.md  
  Project documentation and setup guide.

---

## Prerequisites

Make sure the following tools are installed on your system:

- Docker  
- Docker Compose  

---

## Getting Started

### 1. Clone the Repository

git clone https://github.com/bitlionsecurity/community.git  
cd community

---

### 2. Build and Run the Application

docker-compose up --build

This command will:

- Build all Docker images  
- Start application services  
- Start PostgreSQL database  
- Start Redis  
- Start Nginx web server  

---

### 3. Access the Application

After all containers are running, open your browser and access:

http://localhost:8483

---

## Default Login Credentials

Use the following credentials for initial access:

Email: sadmin@bitlion.io  
Password: bismillah  
OTP Code: 123456  

SECURITY NOTICE:  
Change all default credentials immediately after the first login.

---

## Contributing

We welcome contributions from the community.

To contribute:

1. Fork this repository  
2. Create a new branch for your feature or fix  
3. Commit your changes with clear messages  
4. Submit a Pull Request  

Please ensure your changes follow existing conventions and include relevant documentation.

---

## License

This project is licensed under the MIT License.

---
