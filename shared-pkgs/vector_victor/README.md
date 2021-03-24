A sample command-line application with an entrypoint in `bin/`, library code
in `lib/`, and example unit test in `test/`.

Created from templates made available by Stagehand under a BSD-style
[license](https://github.com/dart-lang/stagehand/blob/master/LICENSE).

## Log

```sh
$ docker run -it --rm -v `pwd`:/myapp -w /myapp google/dart:2.12.2 dart create -t console-full vector_victor
$ cd vector_victor
```

edit pubspec.yml

```sh
$ docker run -it --rm -v `pwd`:/myapp -w /myapp google/dart:2.12.2 dart pub get
# ...
Changed 1 dependency!
```

When upgrading packages

```sh
$ docker run -it --rm -v `pwd`:/myapp -w /myapp google/dart:2.12.2 dart pub upgrade
```

Import libraries from a package
