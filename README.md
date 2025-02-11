# Test Databases

## MySQL 8

Run `docker compose up` in `/docker/mysql` or `npm run docker:mysql` from project root.

### Direct Connection

#### Database

```yaml
hort: localhost
port: 3306
user: root
password: password
```

### SSH Tunnel Connection

#### Database

```yaml
hort: mysql-8-antares
port: 3306
user: root
password: password
```

#### SSH Tunnel

```yaml
hort: localhost
port: 2222
user: tunnel
password: password
```

## PostgreSQL

## SQLite

## Firebird SQL
