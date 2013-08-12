source 'https://rubygems.org'

#ruby '2.0.0'
gem 'rails', '4.0.0'

# Servers
gem 'puma'
gem 'unicorn'

gem 'omniauth'
gem 'omniauth-twitter'
gem 'omniauth-facebook'

# Multi-environment configuration
# gem 'simpleconfig'

# API
# gem 'rabl'

gem 'pg' # for when deployed to heroku
# ORM
gem 'sqlite3' # for local development

# Performance and Exception management
# gem 'airbrake'
# gem 'newrelic_rpm'

# Security
# gem 'secure_headers'

# Miscellanea
# gem 'google-analytics-rails'
 gem 'haml'
# gem 'http_accept_language'
gem 'jquery-rails'
gem 'nokogiri'
gem 'resque', require: 'resque/server' # Resque web interface

# Assets
gem 'coffee-rails', '~> 4.0.0'
gem 'haml_assets'

# gem 'handlebars_assets'
gem 'i18n-js'
gem 'jquery-turbolinks'
gem 'sass-rails', '~> 4.0.0'
gem 'flatstrap-sass'
gem 'therubyracer'
gem 'turbolinks'
gem 'uglifier', '>= 1.3.0'
gem 'angularjs-rails'
gem 'angular-ui-bootstrap-rails'
gem 'font-awesome-sass-rails'

gem 'resque-scheduler'
gem 'foreman'

group :development, :test do
  gem 'delorean'
  gem 'factory_girl_rails'
  gem 'faker'
end

group :development do
  gem 'jazz_hands'
  gem 'bullet'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'
end

group :test do
  gem 'capybara'
  gem 'coveralls', require: false
  gem 'database_cleaner'
  gem 'email_spec'
  gem 'launchy'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
  gem 'simplecov', require: false
  gem 'webmock', require: false
end

group :staging, :production do
  gem 'rails_12factor'
end
