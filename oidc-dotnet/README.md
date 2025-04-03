# OIDC-Dotnet Example

This is a simple example that shows how to secure n dotnet api with keycloak.

## Requirements
- Dotnet
- Docker 

## Setup
* Start the keycloak server by going in the docker directory and start the container with `docker compose up -d`.
* navigate to `localhost:8080` in your browser and login with user `admin` password `admin`
* create a new realm
* creat a client in this realm
* obtain the secret from the client
* insert the needed data in c# code