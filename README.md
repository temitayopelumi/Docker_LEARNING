

## Content

This is a simple Dockerized Flask webpage.

## Technologies used

* Flask framework: Flask is a micro web framework written in Python
* Docker: Docker is a tool designed to make it easier to create, deploy, and run applications by using containers .
* HTML and CSS: HTML and  CSS are the core technologies for building static Web pages.

## Installation

1. Clone the repository
2. Inside the directory, build   an image using the command __docker build -t myimage .__ where myimage is the name of your image.
3. After writing the Dockerfile and building the image from it,  we can run the container with our Python service using the command __docker run -d -p 5000:5000 myimage__.
4. You can now run your webpage on __http://localhost:5000__

## Link to the docker repository

https://hub.docker.com/repository/docker/temitayo19/sca_test


