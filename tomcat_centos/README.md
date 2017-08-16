## dockerStudy tomcat_centos

build tomcat on centos7 with Dockerfile.

### exsample

```
cd <folder>
docker build -t centos7:tomcat .
```

# docker run --privileged --rm -d -p 8080:8080 --name tomcat centos7:tomcat /sbin/init
