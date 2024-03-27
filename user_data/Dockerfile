FROM mysql:8.0

ENV MYSQL_ROOT_PASSWORD 1234
ENV MYSQL_DATABASE ABCompany
ENV MYSQL_USER user_service
ENV MYSQL_PASSWORD 123

ADD ./ABCompany.sql /docker-entrypoint-initdb.d/
