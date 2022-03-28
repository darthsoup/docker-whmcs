ARG MYSQL_VERSION
FROM mariadb:10.5

COPY my.cnf /etc/mysql/conf.d/my.cnf
RUN chmod 0444 /etc/mysql/conf.d/my.cnf

CMD ["mysqld"]

EXPOSE 3306
