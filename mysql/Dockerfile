FROM mysql:latest

MAINTAINER eastpiger @ Geek Pie Association

COPY ./mysqld.cnf /temp/mysqld.cnf

RUN cat /temp/mysqld.cnf >> /etc/mysql/my.cnf
