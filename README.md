# Rails 4 Skeleton

Boilerplate for my Rails 4 projects.

# What it comes with

## Back-End
1. Rails 4.2
1. PostgreSQL
1. rspec/capybara/factory_girl/faker/[shoulda](https://github.com/thoughtbot/shoulda)/vcr
1. capistrano 3.3.x (nginx/passenger)

## Front-End
1. twitter-bootstrap-rails
1. font-awesome-rails
1. jquery-ui-sass-rails
1. jquery-ui-sass-rails

Also, no Coffeescript (I like my scripts in vanilla js).

See the Gemfile for complete listing.

# How to get started

```
git clone git@github.com:adibsaad/rails-4-skeleton.git app_name
cd app_name
rm -rf .git
```

Rename these to match your app's name:
- The module name in ./config/application.rb.
- The session store key name in ./config/initializers/session_store.rb.
- The main layout's title in ./app/views/layouts/application.html.erb.
- Database name/username/passwords/etc. in config/database.yml.
