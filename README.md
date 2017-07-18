# Docker Container based on Centos 7 with systemd

based on https://github.com/docker-library/docs/tree/master/centos#dockerfile-for-systemd-base-image

# Supported tags and respective `Dockerfile` links

 - [`7`, `latest` (7/Dockerfile)](https://github.com/docker-zone/docker-centos-systemd/blob/centos7/7/Dockerfile)
 
Subscribe to project updates by watching the [docker-centos-systemd GitHub repo](https://github.com/docker-zone/docker-centos-systemd/).
 
# Get this image

The recommended way to get the Dingwenxiang0 CentOS Systemd Docker Image is to pull the prebuilt image from the [Docker Hub Registry](https://hub.docker.com/r/dingwenxiang0/centos-systemd/).

```bash
docker pull dingwenxiang0/centos-systemd
```

To use a specific version, you can pull a versioned tag. You can view the [list of available versions](https://hub.docker.com/r/dingwenxiang0/centos-systemd/tags/) in the Docker Hub Registry.

```bash
docker pull dingwenxiang0/centos-systemd:[TAG]
```

# Running Container based on systemd

`docker run --privileged -tid -v /sys/fs/cgroup:/sys/fs/cgroup:ro --name dingwx dingwenxiang0/centos-systemd:[TAG]`

# Open a shell on it, you can try 'systemctl' for instance

`docker exec -it dingwx bash`

# Kill and remove the container

`docker rm -f dingwx`
