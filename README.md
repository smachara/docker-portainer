# docker-portainer

# How to use this image

I recommend you clone this repo and modify the files, then use docker compose to get started quickly.

git clone https://github.com/smachara/docker-portainer.git myportainer && cd myportainer

docker-compose up -d

Voilà, you can now access Portainer by pointing your web browser at http://DOCKER_HOST:9001

Ensure you replace DOCKER_HOST with address of your Docker host where Portainer is running.

You’ll then be prompted to specify a new password for the admin account. After specifying your password, you’ll then be able to connect to the Portainer UI.
