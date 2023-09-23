FROM centos:7

RUN yum -y install httpd

ADD website.tar.gz /var/www/html 

CMD [ "-D","FOREGROUND" ]

ENTRYPOINT [ "/usr/sbin/httpd" ]

EXPOSE 80