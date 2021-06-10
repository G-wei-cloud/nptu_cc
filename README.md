## git github
### install git:
```sh
$ sudo apt-get install git
```

### Use git clone this program:
```sh
# git clone https://github.com/G-wei-cloud/nptu_cc.git 
```

### check if the file different:
```sh
# git status
```

### add index on file:
```sh
# git add <file name>
```

### git commit:
```sh
# git commit -m 'add commit'
```

### upload file:
```sh
# git push
```

## docker
### Start service:
```sh
$ docker-compose up -d
```

### Rebuild specific service:
```sh
$ docker-compose up -d --no-deps --build <server name>
```

### restart service:
```sh
$ docker-compose restart
or
$ docker-compose restart <server name>
```

### check all container:
```sh
$ docker ps
or
$ docker ps -a
```

### stop container:
```sh
$ docker stop <server name>
```

### Stop service:
```sh
$ docker-compose down
```

### Access a running conto=ainer
```sh
$ docker-compose exer $SERVICE_NAME bash
```
