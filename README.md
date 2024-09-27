# rye example

## repl

```bash
# start
$ docker compose -f docker-compose-repl.yml run rye-app-repl

# exit
ctrl + c

# down
$ docker compose -f docker-compose-repl.yml down --remove-orphans
```

## web server

```bash
# build
$ docker compose -f docker-compose-web.yml build

# start http://localhost:8085/ryeshell/
$ docker compose -f docker-compose-web.yml up -d
```
