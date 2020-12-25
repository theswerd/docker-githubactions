# Docker CD with Github Actions

<img src="https://github.com/theswerd/docker-githubactions/blob/main/action+docker.jpg?raw=true" height="300px"></img>

## Setup

1. In `.github/workflows/deploy-docker-image.yaml` set the environment variables to your username and repository name.

2. Go to https://github.com/ **username/repository** /settings/secrets/actions and create a secret called **DOCKER_HUB_PASSWORD** that is equal to your DockerHub password.

3. Create your project - The **Dockerfile** is empty.
