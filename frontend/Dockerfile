FROM centos
RUN yum update -y
RUN yum -y install httpd
ADD code /var/www/html/
CMD ["apachectl", "-D", "FOREGROUND"]

