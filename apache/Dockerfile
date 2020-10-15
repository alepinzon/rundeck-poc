FROM httpd:2.4

RUN apt-get update && apt-get install -y libapache2-mod-auth-openidc curl

COPY httpd.conf /usr/local/apache2/conf/