# docker-compose-rails-sample

https://docs.docker.com/compose/rails/

docker-compose で Rails/PostgreSQL を動かすサンプル

## 起動

```
$ git clone https://github.com/nobmurakita/docker-compose-rails-sample.git
$ cd docker-compose-rails-sample
$ docker-compose build
$ docker-compose up
```

## データベース作成

別ターミナルで

```
$ docker-compose run web rake db:create
```
