see https://dart.dev/tutorials/server/get-started

## log

```sh
$ docker run -it --rm -v `pwd`:/myapp -w /myapp google/dart:2.12.2 dart create -t console-full cli
$ cd cli
```

create Dockerfile, docker-compose.yml

```sh
$ docker-compose run --rm app
# in container
$ dart --disable-analytics
$ dart run
Hello world: 42!
$ dart compile exe bin/cli.dart
Generated: /app/bin/cli.exe
$ time bin/cli.exe
```
