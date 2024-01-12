# sebinpj/pgbadger

Dockerfile for pgBadger fork from matsuu/pgbadger

##  Usage

### Images

* Docker Hub: [sebinpj/pgbadger](https://hub.docker.com/r/sebinpj/pgbadger/)

### PostgreSQL with default prefix

```
cat slow.log | docker run -i --rm sebinpj/pgbadger - -o - -x html > out.html
```

### RDS for PostgreSQL

```
cat slow.log | docker run -i --rm sebinpj/pgbadger -f rds - -o - -x html > out.html
```

### help

```
docker run -i --rm sebinpj/pgbadger --help
```

## References

* [pgBadger official site](https://pgbadger.darold.net/)
* GitHub [sebinpj/docker-pgbadger](https://github.com/sebinpj/docker-pgbadger)
* Original Repo [matsuu/docker-pgbadger](https://github.com/matsuu/docker-pgbadger)
* Docker Hub [sebinpj/pgbadger](https://hub.docker.com/r/sebinpj/pgbadger/)
