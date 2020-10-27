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


`bundle exec rails g spree:install --user_class=Spree::User`
`bundle exec rails g spree:auth:install`
`bundle exec rails g spree_gateway:install`

`bundle exec rake railties:install:migrations`
`bundle exec rails db:migrate`
`bundle exec rails db:seed`
`bundle exec rake spree_sample:load`
`bundle exec rails g spree:frontend:copy_storefront`