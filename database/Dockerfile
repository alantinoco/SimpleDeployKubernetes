FROM mysql:5.7

WORKDIR /var/lib/mysql

ENV MYSQL_ROOT_PASSWORD=admin

ENV MYSQL_DATABASE=meuBanco

ADD sql.sql /docker-entrypoint-initdb.d

EXPOSE 3306