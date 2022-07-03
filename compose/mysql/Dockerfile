FROM mysql

MAINTAINER Ewerton Vieira Donati <ewertonvd@gmail.com>

#ENV MYSQL_USER=root \
#    MYSQL_DATABASE=fiapdb \
#    MYSQL_ROOT_PASSWORD=senhaFiap

ADD ./aso.sql /docker-entrypoint-initdb.d
