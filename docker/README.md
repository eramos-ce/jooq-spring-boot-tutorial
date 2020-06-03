# Jooq / Boot Docker Configs

Provides docker build and runtime configurations.

## Containers
- postgis
    * Contains the PostGIS DB container.
    * Connectivity parameters:
        * Within another container: postgis:5432
        * From local host: localhost:5432
    * Environment variables
        * `POSTGRES_USER`
        * `POSTGRES_PASSWORD`
        * `POSTGRES_DB`