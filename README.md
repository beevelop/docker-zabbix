[![Travis](https://img.shields.io/travis/beevelop/docker-zabbix.svg?style=flat-square)](https://travis-ci.org/beevelop/docker-zabbix)
[![Docker Pulls](https://img.shields.io/docker/pulls/beevelop/zabbix.svg?style=flat-square)](https://links.beevelop.com/d-zabbix)
[![ImageLayer](https://badge.imagelayers.io/beevelop/zabbix:latest.svg)](https://imagelayers.io/?images=beevelop/zabbix:latest)
[![Beevelop](https://links.beevelop.com/honey-badge)](https://beevelop.com)

# Zabbix 3 (Server)

> Zabbix 3 is still in Alpha and should not be used in production. This Docker images is thought to give you a preview of the upcoming great release (IMHO) :cookie:

----
### Pull from Docker Hub
```
docker pull beevelop/zabbix:latest
```

### Build from GitHub
```
docker build -t beevelop/zabbix github.com/beevelop/docker-zabbix
```

### Run image
```
docker run -it beevelop/zabbix bash
```

### Use as base image
```Dockerfile
FROM beevelop/zabbix:latest
```