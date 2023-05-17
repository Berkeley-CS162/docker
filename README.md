# CS 162 Docker-Based Workspace

## Tools you'll need installed
- [Docker Desktop](https://docs.docker.com/desktop/)

**OR**

- [Docker Engine](https://docs.docker.com/engine/) **AND** [Docker Compose](https://docs.docker.com/compose/)

## Running the Workspace
> Docker commands will generally have to be run with "sudo", so if you see usage of `docker-compose`, you might need to use `sudo docker-compose`

```bash
git clone https://github.com/Berkeley-CS162/docker.git
cd docker
docker-compose up -d
```

## SSHing into the Workspace
```bash
ssh vagrant@127.0.0.1 -p 16222
```
When prompted for a password, enter: `vagrant`

## Stopping the Workspace
```bash
docker-compose down
```

## Resetting the Workspace
```bash
sudo rm -rf .workspace
```
