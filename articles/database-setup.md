# Database Setup
This guide covers the database setup for XAuth.

## Supported Databases
XAuth supports the following databases:
- SQLite (default)
- MySQL
- MariaDB

## SQLite
SQLite is the default database and requires no special configuration. The database file will be created automatically.

## MySQL / MariaDB
To use MySQL or MariaDB, you need to change the `database.type` setting in your `config.yml` to `mysql`.

Example configuration:
```yaml
database:
  type: mysql
  mysql:
    host: 127.0.0.1
    port: 3306
    user: xauth
    password: "your_password"
    database: xauth
```

Make sure to create the database and user in your MySQL/MariaDB server before starting the XAuth server.
