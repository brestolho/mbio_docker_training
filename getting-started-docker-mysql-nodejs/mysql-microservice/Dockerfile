FROM mysql:5.7
ENV MYSQL_DATABASE=test \
MYSQL_ROOT_PASSWORD=password
COPY ./test-dump.sql /docker-entrypoint-initdb.d/
