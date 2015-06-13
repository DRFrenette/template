# Rails 4 Skeleton

Boilerplate for my Rails 4 projects.

# What it comes with

## Back-End
1. Rails 4.2
1. PostgreSQL
1. rspec/capybara/factory_girl/guard/[shoulda](https://github.com/thoughtbot/shoulda)

## Front-End
1. twitter-bootstrap-rails
1. font-awesome-rails
1. jquery-datatables
1. jquery-validation-plugin

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

## Guard

Guard is included, which has
[guard-rails](https://github.com/ranmocy/guard-rails),
[guard-rspec](https://github.com/guard/guard-rspec) and
[guard-livereload](https://github.com/guard/guard-livereload). Start the app by
typing ```guard```.

