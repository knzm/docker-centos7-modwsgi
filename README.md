# docker-centos7-modwsgi

This repo contains a Dockerfile for Apache + modwsgi on CentOS 7.

## Build

```
# docker build --rm -t knzm/centos7-modwsgi .
```

## Usage

To run (if port 8000 is available and open on your host):

```
# docker run -p 8000:80 -d knzm/centos7-modwsgi
```

## Test

```
# curl http://localhost:8000
```
