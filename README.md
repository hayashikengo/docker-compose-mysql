# docker-compose-mysql
mysql db example.
- simply mysql database image
- perpetuate database by overlay data files

### run db
```bash
$ docker-compose up
```

### login
```bash
$ docker exec -it mydb mysql -u root -p111 mydb
```

# LICENSE
[MIT](https://github.com/hkengo/docker-compose-mysql/blob/main/LICENSE)