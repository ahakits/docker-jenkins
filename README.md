# docker-jenkins

Local Jenkins for Docker for Mac.

## Requirement

- Docker for Mac

## Usage

1. `cd ./docker`
2. add plugins to `./jenkins/plugins.txt`
3. `docker-compose up -d`
4. open http://localhost:8080
5. paste `../data/jenkins/secrets/initialAdminPassword` for Unlock Jenkins
