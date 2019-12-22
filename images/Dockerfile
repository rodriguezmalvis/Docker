FROM centos:7
RUN yum -y install httpd
WORKDIR /var/www/html
COPY beryllium .
ENV contenido prueba
RUN echo "$contenido" > ./prueba.html
EXPOSE 8080
CMD apachectl -DFOREGROUND
