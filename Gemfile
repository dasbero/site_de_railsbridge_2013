source "https://rubygems.org"

gem "rails", "3.2.12"
gem "haml-rails",   "~> 0.4"
gem "jquery-rails"
gem "font-awesome-rails"
gem "twitter"
gem "tweetstream"

group :production do
  gem "pg"
end

group :assets do
  gem "sass-rails",   "~> 3.2.3"
  gem "coffee-rails", "~> 3.2.1"
  gem "bootstrap-sass-rails", "~> 2.3.2.0"
  gem "uglifier",     ">= 1.0.3"
  gem "bourbon",      "~> 3.1.8"
end

group :test, :development do
  gem "sqlite3"

  # Testing
  gem 'rspec-rails'
  gem 'capybara'
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'timecop'
  gem 'simplecov', :require => false

  # Debugging
  gem "quiet_assets"
  gem "jazz_hands"
end

group :development do
  gem "thin"
  gem "better_errors"
  gem "binding_of_caller"
end
