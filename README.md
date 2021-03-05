![multipostgres image](https://github.com/geospin-takelage/takelage-img-multipostgres/actions/workflows/build_deploy_multipostgres_nightly.yml/badge.svg)

# takelage-img-multipostgres

The
[takelage/multipostgres](https://hub.docker.com/repository/docker/takelage/multipostgres)
docker image is based on
[oostgres:11](https://hub.docker.com/_/postgres).
It has been updated and it accepts the 
`POSTGRES_MULTIPLE_DATABASES` environment variable using
[this idea](https://github.com/mrts/docker-postgresql-multiple-databases).

## Framework

The takelage devops framework consists of these projects:

| App | Description |
| --- | ----------- |
| *[takelage-doc](https://github.com/geospin-takelage/takelage-doc)* | takelage documentation |
| *[takelage-dev](https://github.com/geospin-takelage/takelage-dev)* | takelage development environment |
| *[takelage-var](https://github.com/geospin-takelage/takelage-var)* | takelage test plugin |
| *[takelage-cli](https://github.com/geospin-takelage/takelage-cli)* | takelage command line interface |
| *[takelage-bit](https://github.com/geospin-takelage/takelage-bit)* | takelage bit server | 
| *[takelage-img-takelbase](https://github.com/geospin-takelage/takelage-img-takelbase)* | takelage takelbase image | 
| *[takelage-img-takelslim](https://github.com/geospin-takelage/takelage-img-takelslim)* | takelage takelbase image | 
| *[takelage-img-multipostgres](https://github.com/geospin-takelage/takelage-img-multipostgres)* | takelage multipostgres image | 

