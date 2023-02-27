# Flask-Redis Docker Compose

#### This project is designed to help you set up a Flask web application with Redis using Docker Compose. The main purpose of the application is to count the number of times a page has been viewed.

## Prerequisites

#### To run this project, you will need to have the following installed:

- Docker
- Docker Compose
- Git

## Getting Started

1. Clone this repository to your local machine.

```bash
git clone https://github.com/NurlanEmilbekuulu/flask-redis-docker-compose.git
```

2. Navigate to the cloned repository.

```bash
cd flask-redis-docker-compose
```

3. Create Dockerfile to build image from python code.
4. Create docker-compose.yml to manage containers from Dockerfile from previous step and official redis image.
5. Start the application using Docker Compose.
```bash
docker-compose up
```