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

# Docker

```
docker build -t basic_ror_web_deploy .
docker run -p 80:80 -e RAILS_MASTER_KEY=0fc668b95ea47c13900c3b736002ab69 --name basic_ror_web_deploy basic_ror_web_deploy
```
