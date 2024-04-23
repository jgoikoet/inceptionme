FROM debian:bullseye

RUN apt-get update
RUN apt-get -y install mariadb-server
RUN service mariadb start

CMD ["mysqld"]

#ENV MYSQL_ROOT_PASSWORD=pass 