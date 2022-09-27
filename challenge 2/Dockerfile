FROM centos:7.9.2009

RUN yum -y install httpd

ADD webserver.tar.gz /var/www/html/

CMD ["usr/sbin/httpd" "-D", "FOREGROUND" ]

ENTRYPOINT [ "/usr/sbin/httpd" ]

EXPOSE 80