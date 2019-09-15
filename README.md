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



```
  rails g model task title:string description:text company:string url:string
  rake db: migrate
  rails g controller tasks

  // add routes
  resources :tasks
  root "tasks#index"
  // add inedx to tasks controller
  def index
  end 

  // add gems
  gem 'haml', '~> 5.1', '>= 5.1.2'
  gem 'simple_form', '~> 4.1'
  gem 'bootstrap-sass', '~> 3.4', '>= 3.4.1'

  // follow guideline here to install bootstrap
  https://github.com/twbs/bootstrap-sass/

  // follower guideline here to install simple_form 
  https://github.com/plataformatec/simple_form/

  // setup tasks controller 
  index, show, new, create, edit, update, destroy,
  // set up their view files 

  
``` 