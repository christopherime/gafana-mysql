# grafana-mysql

Grafana application using external mysql

## config/grafana.ini

```ini
[database]
type = mysql
host = <YOUR_IP>:3306
name = <DATABASE_NAME>
user = <USERNAME_DATABASE>
password = <PASSWORD>
```

## MYSQL Variables

```docker-compose
MYSQL_USER: <USERNAME_DATABASE>
MYSQL_PASSWORD: <USERNAME_DATABASE>
MYSQL_DATABASE: <DATABASE_NAME>
```

## TODO

Do the documentation for it
