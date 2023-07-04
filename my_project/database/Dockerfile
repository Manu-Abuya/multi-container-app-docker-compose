# PostgreSQL image as the base image
FROM postgres:13

# Copy the initialization script into the container
COPY init.sql /docker-entrypoint-initdb.d/

# Expose the default PostgreSQL port
EXPOSE 5432

