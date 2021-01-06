# Docker-Compose for old lamp stack + traefik

- apache 2.4
- php 5.6.40
- mysql 5.7.32
- traefik 2.3

## how to use


0/ clone the project in your server and make sure the DNS server is well configured.

1/ put your web php application in the ./web directory.

2/ change the ligne 20 in docker-compose.yml file with the coresponding domaine name.

3/ run your application.

- > docker-compose up -d