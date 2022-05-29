- give permission to entrypoint.sh
```
sudo chmod +x entrypoint.sh
```
- build image
```
 docker build -t pgbouncer .
```
- docker compose command
```
password=x1 user=x2 db=x3 docker-compose -f docker-compose2.yml up
```
- to connect to pgbouncer using this command
```
psql postgres://x2:x1@localhost/x3
```
