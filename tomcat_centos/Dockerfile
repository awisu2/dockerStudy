# exsample command docker build -t centos7:tomcat .
FROM centos:7 AS centos7

# create centos7 development
RUN yum update -y
RUN yum groupinstall -y "Development Tools"
RUN yum install -y vim

RUN yum install -y tomcat tomcat-admin tomcat-docs tomcat-examples
