FROM mysql:8.0

ENV MYSQL_ROOT_PASSWORD 123
ENV MYSQL_DATABASE user_data
ENV MYSQL_USER user
ENV MYSQL_PASSWORD 123

ADD ABCompany.sql /docker-entrypoint-initdb.d
