# File for development for the entire project

## requirements

### git clone all repo's

```bash
git clone git@github.com:vives-projectwerk-2021/pulu-ttn-listener.git
git clone git@github.com:vives-projectwerk-2021/pulu-backend.git
git clone git@github.com:vives-projectwerk-2021/pulu-frontend.git
git clone git@github.com:vives-projectwerk-2021/ttn-pulu-device-manager-api.git
```
### Install docker

https://docs.docker.com/get-docker/
Docker desktop has docker-compose on windows, for other platforms you need to install docker-compose aswell.
https://docs.docker.com/compose/install/


### fill in the .env file

.Fill in the .env file, example of the structure is in the .env.example
[Environment example](https://github.com/vives-projectwerk-2021/pulu-docker-compose/blob/master/.env.example)

### keep the required repo's up to date

git pull for all repo's to keep them uptodate.

### run the docker-compose file

run this in the pulu-docker-compose directory.

```bash
docker-compose up
```

## Versions of the databases

influxdb:2.0.8-alpine
mongo:4.4.9
