# Docker Containers for PostgreSQL and pgAdmin

Creates two Docker containers, one with PostgreSQL the other with pgAdmin.

## Folders

Two folders need to be created to store persistant data for each container.

### db-data

This folder contains the PostgreSQL data files

### pgadmin-data

This folder contains the pgAdmin data files

## Create .env to keep all private variables

The follwing is a sample with basic default repsonses in it.

```.env
POSTGRES_DB="postgres"
POSTGRES_USER="admin"
POSTGRES_PASSWORD="password"

PGADMIN_DEFAULT_EMAIL="user@email.com"
PGADMIN_DEFAULT_PASSWORD="password"
PGADMIN_LISTEN_PORT=8080
```
