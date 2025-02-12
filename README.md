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

Run `docker compose up` in `/docker/pg` or `npm run docker:pg` from project root.

### Direct Connection

#### Database

```yaml
hort: localhost
port: 5432
user: postgres
password: password
```

### SSH Tunnel Connection

#### Database

```yaml
hort: pg-antares
port: 5432
user: postgres
password: password
```

#### SSH Tunnel

```yaml
hort: localhost
port: 2223
user: tunnel
password: password
```

## SQLite

In `sqlite` folder there are some databases available to connect to.

## Firebird SQL
