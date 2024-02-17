# Examples of docker compose files

### Keycloak and MySQL

- Keycloak will check healthy status of the db container before start
- The MySQL volume will be created on the local directory of the docker compose file
- After started access keycloak on http://localhost:8080
- [Docker compose file](https://github.com/james-freitas/docker-compose-samples/blob/main/keycloak-mysql/docker-compose.yml)