# Setup

This project is run via `docker` and `docker-compose`. Make sure both are installed.

Set the environment variables, e.g. by creating the file `.env` with following content:

```
FQDN=git.example.org

DB_NAME=gitea
DB_USER=gitea
DB_PASS=my_secret_password

PATH_SSL_CERT=/path/to/ssl-certs/fullchain.pem
PATH_SSL_KEY=/path/to/ssl-certs/privkey.pem
PATH_SSL_DIR=/path/to/ssl-certs
```

To start the app, run:

```
docker-compose up -d
```
