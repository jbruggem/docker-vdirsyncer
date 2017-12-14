# docker-vvdirsyncer

A docker for [vdirsyncer](https://github.com/pimutils/vdirsyncer)

# Usage

```
docker build -t jbruggem/vvdirsyncer:latest .
docker run --rm -i --user=$UID -v$PWD/config:/config -v$PWD/data:/data  jbruggem/vvdirsyncer
```