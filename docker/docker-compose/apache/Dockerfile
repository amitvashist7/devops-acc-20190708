# Base Image
FROM ubuntu:16.04

# Owner
MAINTAINER Amit Vashist <amitvashist7@gmail.com>

# Update Ubuntu Repo.
RUN apt-get update

# Install Apache Packages
RUN apt-get install apache2 -y 

# Custom WebPage
COPY helloworld.html /var/www/html/hello.html

# RUN the Service 
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
