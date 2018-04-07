# Build image
> docker build -t IMAGE_NAME .

# Create container
> docker run --name CONTAINER_NAME -d webserver

# Connect with container
> docker exec -it CONTAINER_ID bash