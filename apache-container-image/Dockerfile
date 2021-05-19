FROM centos:latest
MAINTAINER Bruno <brestolho@gmail.com>
LABEL description="A custom Apache container based on CentOS"
RUN yum install -y httpd && \
     yum clean all
RUN echo "Hello from Dockerfile" > /var/www/html/index.html
EXPOSE 80
CMD ["httpd", "-D", "FOREGROUND"]
