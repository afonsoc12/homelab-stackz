# Homelab Stackz
A set of docker-compose files.

_**This is under heavy maintenance. Stay tuned!**_

# Instructions
1. Edit the *.env files
2. To run a stack:
```shell
docker-compose -p media --env-file media-compose.env -f media-compose.yml up -d
```