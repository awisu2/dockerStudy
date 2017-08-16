## dockerStudy Dockerfile

simple Dockerfile useage.
this study create centos7 yum update images.

### exsample

build

```
cd <folder>
docker build -t centos7:develop .
docker images
```

run

```
docker run --rm -it --name centos7_develop centos7:develop
```

## if want run systemctl command

run

```
docker run --privileged --rm -d --name centos7_develop centos7:develop /sbin/init
docker ps
docker exec -it centos7_develop /bin/bash
```

stop

```
docker stop centos7_develop
docker ps -a
```
