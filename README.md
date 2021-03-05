[![multipostgres image](https://github.com/geospin-takelage/takelage-img-multipostgres/actions/workflows/build_deploy_multipostgres_nightly.yml/badge.svg)](https://github.com/geospin-takelage/takelage-img-multipostgres/actions/workflows/build_deploy_multipostgres_nightly.yml)
[![docker image](https://img.shields.io/docker/v/takelage/multipostgres/latest?label=hub.docker.com&color=blue)](https://hub.docker.com/repository/docker/takelage/multipostgres)
[![license](https://img.shields.io/github/license/geospin-takelage/takelage-img-multipostgres?color=red)](https://github.com/geospin-takelage/takelage-img-multipostgres/blob/main/LICENSE)

# takelage-img-multipostgres

The
[takelage/multipostgres](https://hub.docker.com/repository/docker/takelage/multipostgres)
docker image is based on
[postgres:11](https://hub.docker.com/_/postgres).
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

