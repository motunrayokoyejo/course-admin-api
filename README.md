## Course Admin API
This repository contains a FastAPI application for managing courses and chapters, including endpoints for retrieving course data, chapter details, and rating chapters.
The application is containerized using Docker for easy deployment.

### Setup
Prerequisites
Ensure you have the following installed:

- Python 3.9+
- Docker

### Clone the Repository
To clone this repository, use the following command:

- git clone https://github.com/motunrayokoyejo/course-admin-api/
- cd course-admin-api

### Run the Application

Build the Docker Image:

docker build -t my_python_app .

### Run the Docker Container:

docker run -d -p 8080:80 my_python_app

The application will be accessible at http://localhost:8080.

### Documentation
Code documentation can be found at http://localhost:8080/docs

