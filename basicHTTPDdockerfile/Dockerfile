FROM centos:7
LABEL creator = "Varsharani"
RUN yum install httpd -y
RUN echo "hello world" > /var/www/html/index.html 

EXPOSE 80
CMD httpd -DFOREGROUND
