FROM postgres:latest

ENV POSTGRES_USER=postgres
ENV POSTGRES_PASSWORD=example
ENV POSTGRES_DB=mydatabase

COPY init.sql /docker-entrypoint-initdb.d/

EXPOSE 5432