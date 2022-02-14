# Docker Ubuntu SSH

## Build

```shell
docker build -t ubuntu-ssh .
```

## Usage

```shell
docker run -itd -p YOUR_SSH_PORT:22 -p YOUR_WEB_PORT:80 -e NAME=YOUR_USER_NAME -e PASSWORD=YOUR_PASSWORD -h YOUR_HOST_NAME --name YOUR_CONTAINER_NAME ubuntu-ssh
```