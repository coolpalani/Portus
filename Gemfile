# frozen_string_literal: true

source "https://rubygems.org"

gem "active_record_union"
gem "base32"
gem "devise", ">= 4.6.1"
gem "font-awesome-rails", ">= 4.7.0.4"
gem "grape", ">= 1.2.3"
gem "grape-entity"
gem "grape-swagger", ">= 0.32.1"
gem "grape-swagger-entity", ">= 0.3.2"
gem "gravatar_image_tag"
gem "hashie-forbidden_attributes"
gem "jwt"
gem "kaminari"
gem "net-ldap"
gem "omniauth-github", ">= 1.3.0"
gem "omniauth-gitlab", ">= 2.0.0"
gem "omniauth-google-oauth2", ">= 0.6.0"
gem "omniauth-openid", ">= 1.0.1"
gem "omniauth_openid_connect", ">= 0.2.4"
gem "public_activity", "~> 1.6.3"
gem "pundit"
gem "rails", "~> 5.2.2"
gem "redcarpet"
gem "sassc-rails", ">= 2.1.0"
gem "search_cop"
gem "slim"
gem "webpack-rails", ">= 0.9.11"

gem "rack-cors"

# Supported DBs
gem "mysql2", group: :db
gem "pg", group: :db

# Pinning these specific versions because that's what we have on OBS.
gem "ethon"
gem "typhoeus"

# Used to store application tokens.
gem "bcrypt"

# If the deployment is done through Puma, include it in the bundle.
gem "puma"

# Configuration management
gem "cconfig", "~> 1.2.0"

# Pinning some versions
gem "i18n"
gem "ice_nine"
gem "minitest"
gem "multi_json"
gem "rails-dom-testing"
gem "sprockets", ">= 3.7.2"
gem "sprockets-rails", ">= 3.2.1"
gem "temple"

##
# The following groups will *not* be included on the production installation.

group :assets do
  gem "bootstrap-sass"
  gem "uglifier"
end

group :development do
  gem "annotate"
  gem "git-review", require: false
  gem "guard", require: false
  gem "guard-rspec", require: false
  gem "guard-rubocop", require: false
  gem "pry-rails"
  gem "rack-mini-profiler", ">= 1.0.2", require: false
  gem "rails-erd"
  gem "web-console", ">= 3.7.0"
end

group :development, :test do
  gem "rspec-core"
  gem "rspec-rails", ">= 3.8.2"

  gem "awesome_print"
  gem "binman"
  gem "brakeman", require: false
  gem "byebug"
  gem "database_cleaner"
  gem "factory_bot_rails", ">= 5.0.1"
  gem "ffaker"
  gem "grape-swagger-rails", ">= 0.3.1"
  gem "hirb"
  gem "rubocop", require: false
  gem "wirb"
  gem "wirble"
end

group :test do
  gem "capybara", ">= 3.13.2"
  gem "capybara-screenshot", ">= 1.0.22"
  gem "chromedriver-helper"
  gem "docker-api"
  gem "json-schema"
  gem "poltergeist", ">= 1.18.1", require: false
  gem "rails-controller-testing", ">= 1.0.4"
  gem "selenium-webdriver"
  gem "shoulda"
  gem "simplecov", require: false
  gem "timecop"
  gem "vcr"
  gem "webmock", require: false
end
