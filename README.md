# Wordpress-Dev-With-Docker
Effortlessly Spin up a development environment for Wordpress using Docker

Build the project
Now, run docker-compose up -d from your project directory.

This runs docker-compose up in detached mode, pulls the needed Docker images, and starts the wordpress and database containers

You can now access your wordpress envornment by accessing - http://localhost:8000 in a web browser.

Stopping the container
To stop your wordpress container, you can issue the below command:
       docker-compose down
