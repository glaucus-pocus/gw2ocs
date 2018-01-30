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

## Usage

**Start the server**  
```sh
docker-compose up
docker-compose run web rake db:create
```

**Stop the server**  
```sh
docker-compose down
```