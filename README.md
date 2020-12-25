# Docker CD with Github Actions

Docker Github Actions Starter

## Setup

1. In `.github/workflows/deploy-docker-image.yaml` set the environment variables to your username and repository name.

2. Go to https://github.com/**username/repository**/settings/secrets/actions and create a secret called **DOCKER_HUB_PASSWORD** that is equal to your DockerHub password.

3. Create your project - The **Dockerfile** is empty.
