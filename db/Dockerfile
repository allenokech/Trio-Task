# Derived from official mysql image (our base image)
FROM mysql
# Add a database
ENV MYSQL_DATABASE test-db
# Add the content of the .sql file to your image
# All scripts in docker-entrypoint-initdb.d/ are automatically
# executed during container startup
COPY ./db/ docker-entrypoint-initdb.d/