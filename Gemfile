source "https://rubygems.org"
ruby "2.1.5"

gem "rails", "4.2.0"

gem "shopify_app", "~> 5.0.2"
gem "jquery-rails"
gem "quiet_assets"
gem "sqlite3"

group :assets do
  gem "sass-rails"
  gem "coffee-rails"
  gem "uglifier", ">= 1.0.3"
end

group :development, :test do
  gem "thin"
  gem "less-rails-bootstrap"
  gem "therubyracer", platforms: :ruby
  gem "pry-rails"
  gem "sqlite3"
  gem 'capistrano-rails', '~> 1.1.1'
  gem 'capistrano-rvm'
  gem 'capistrano-bundler'
end

gem 'unicorn'

group :production do
  gem "pg"
end
