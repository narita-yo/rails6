# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


https://qiita.com/naokit-dev/items/99225bf3d8665ecfdec2

webpackerのインストール  
docker-compose run app rails webpacker:install  

docker-compose build  
docker-compose up  
docker-compose run app rails webpacker:install  
docker-compose run app rails webpacker:install:vue  
docker-compose run app rails db:create  

コンテナに入る
docker exec -it techpit_rails_vue_app_1 /bin/ash

