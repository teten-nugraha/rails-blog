# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...

docker-compose run web rake db:create
docker-compose run web rake routes
docker-compose run web rake db:migrate
docker-compose run web rails g migration create_articles
docker-compose run web rails c
docker-compose run web rails g migration add_description_to_articles
