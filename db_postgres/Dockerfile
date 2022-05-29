FROM postgres:9.6
COPY ./resources/db/*.sql /docker-entrypoint-initdb.d/
RUN chmod -R +x /docker-entrypoint-initdb.d/