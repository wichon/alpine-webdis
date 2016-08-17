# alpine-webdis
Webdis running in a slim Alpine based Docker container.

Webdis is a Redis HTTP interface with JSON output http://webd.is/

## Build
```
docker build --no-cache -t [image-name]:latest .
```

## Usage
This container is intended to be used as a base for custom configured Webdis setups, configuration can be easily overwritted in a Dockerfile (Webdis binary and config reside in /webdis folder).
