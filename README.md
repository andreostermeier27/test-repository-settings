# <repository-name>

## [Description](#description)

High level description of the purpose of this repository

## [Owner](#owner)

Add at least two contacts, that know about the details of the code and the functionality stored in this repository.

mailto: andre.ostermeier@relayr.io
mailto: andre.ostermeier@relayr.io

## [Status](#status)

Add Jenkins / SonarQube information (badges) via markdown language

| Build Status master |SonarQube URL  | Quality Gate master| 
| :---        |    :----  |          ---: |
|[![Build Status](https://pseci.coderetro.net/job/Buildroot/job/buildroot-os-relayr/badge/icon)](https://pseci.coderetro.net/job/Buildroot/job/buildroot-os-relayr/badge/icon)|[https://psesq.coderetro.net/dashboard?id=John](https://psesq.coderetro.net/dashboard?id=John)|[![Quality Gate Status](https://psesq.coderetro.net/api/project_badges/measure?project=John&metric=alert_status)](https://psesq.coderetro.net/dashboard?id=John)|

## [Links](#links)

Gather links to technical documentation in WIKI etc.

Link to README.md template: https://relayr.atlassian.net/wiki/spaces/psengineering/pages/edit-v2/1415807886

#---------------------------------------------------------------------------------------------------------------#

# Additional Information

## [Dependencies](#dependencies)

- [cloud-browser-sdk](https://github.com/relayr/cloud-browser-sdk)

## Running as a Docker container

To run as a Docker container, please use the following command as an example:

```
docker run --rm -e ENVIRONMENT=rlr-eu-stg -e CONSUL_HOST=consul.rlr-eu-stg -e CONSUL_HTTP_TOKEN=XXXXXXX -p 8080:80 relayr/cloud-modules-user:master_XXX
```

## [Installation](#installation)

The command `npm run reset` deletes `node_modules/` and `package-lock.json`,
and then re-installs the project's dependencies.
