# api-docker
A set of docker configuration files for OneTable API server

## How-to-run

1. [Install docker-compose](https://docs.docker.com/compose/install/#install-compose)

2. Make [init-letsencrypt.sh](https://github.com/adiostone/api-docker/blob/master/init-letsencrypt.sh) to executable

```bash
$ chmod +x ./init-letsencrypt.sh
```

3. Run the init script for issuing https certifications

```bash
$ ./init-letsecnrypt.sh
```

4. And then run docker-compose

```bash
$ docker-compose up -d
```
