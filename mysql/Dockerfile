ARG MYSQL_VERSION
FROM mysql:${MYSQL_VERSION}

COPY my.cnf /etc/mysql/conf.d/my.cnf

CMD ["mysqld"]

EXPOSE 3306
