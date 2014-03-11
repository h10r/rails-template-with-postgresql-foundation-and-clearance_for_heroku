== README

This is a Rails 4 template with PostgreSQL, Heroku, the Foundation template and Thoughtbot's clearance authentication already working.

It is based on the Heroku guide for Rails 4:

https://devcenter.heroku.com/articles/getting-started-with-rails4

== TO DO

* Change AppName to your name
* Update config/database.yml
* Install dependencies
```no-highlight
bundle install
```
* Create databases: 
```no-highlight
rake db:create:all
```
* Migrate databases: 
```no-highlight
rake db:migrate
```
* Update secure secret hash
```no-highlight
rake secret
```

== Based on

Clearance - Rails authentication with email & password.

https://github.com/thoughtbot/clearance

Foundation for Rails

https://github.com/zurb/foundation-rails