## Usage :

- Creates the image and gets the `image_id` : `docker build .`
- Creates a container from this image in interactive mode : `docker run -it image_id`
- Gets the container name (once the abode run has completed): `docker ps -a`
- Start again this container in interactive mode : `docker start -a -i container_name` 
 