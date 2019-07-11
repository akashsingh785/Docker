#Base Image
FROM ubuntu:16.04

#Owner 
MAINTAINER AKASH SINGH <akash.i.singh@accenture.com>

#Update Ubuntu Repo

RUN apt-get update

#Install Apache Packages

RUN apt-get install apache2 -y

#COPY file
COPY hello.html /var/www/html/hello1.html

#Run the service

CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]
