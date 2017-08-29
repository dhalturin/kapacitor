# Kapacitor MySQL Threads Connections
Send alerts at %% connections to the database

# How to enable this tick
```
kapacitor define mysql_connections -type batch -tick mysql_connections.tick -dbrp telegraf.telegraf_7d
kapacitor enable mysql_connections
```
