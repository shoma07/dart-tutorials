FROM google/dart:2.12.2

RUN dart --disable-analytics
WORKDIR /app
ADD pubspec.* /app/
RUN pub get
ADD . /app
