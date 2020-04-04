FROM centos
RUN yum install httpd -y
COPY file /opt/
VOLUME /var/log
EXPOSE 80 443 8080
CMD ["/usr/sbin/httpd","-D","FOREGROUND"]
