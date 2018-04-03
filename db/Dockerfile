FROM postgres:9.5
MAINTAINER mika
ENV POSTGRES_DB postgres
COPY ./init-db.sql /docker-entrypoint-initdb.d/
