source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby File.read('.ruby-version').strip

gem "rails", "~> 7.0.6"

gem 'draper', '~> 4.0', '>= 4.0.2'
gem "cssbundling-rails"
gem "jbuilder"
gem "jsbundling-rails"
gem "pg", "~> 1.1"
gem "puma", "~> 5.0"
gem "redis", "~> 4.0"
gem "sprockets-rails"
gem "stimulus-rails"
gem "turbo-rails"
gem 'whenever', '~> 1.0', require: false

# Use Kredis to get higher-level data types in Redis [https://github.com/rails/kredis]
# gem "kredis"

# Use Active Model has_secure_password [https://guides.rubyonrails.org/active_model_basics.html#securepassword]
# gem "bcrypt", "~> 3.1.7"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Use Sass to process CSS
# gem "sassc-rails"

# Use Active Storage variants [https://guides.rubyonrails.org/active_storage_overview.html#transforming-images]
# gem "image_processing", "~> 1.2"

group :development, :test do
  gem 'annotate', '~> 3.2' # Annotate ActiveRecord models [
  gem 'dotenv-rails', '~> 2.8', '>= 2.8.1' # Loads environment variables from `.env` into `ENV`
  gem 'factory_bot_rails', '~> 6.2' # A fixtures replacement with a straightforward definition syntax, support for multiple build strategies (saved instances, unsaved instances, attribute hashes, and stubbed objects), and support for multiple factories for the same class (user, admin_user, and so on), including factory inheritance
  gem 'faker', '~> 3.2' # A library for generating fake data such as names, addresses, and phone numbers
  gem 'pry-byebug', '~> 3.10', '>= 3.10.1' # Adds next/step commands and a pry-byebug command to start a debugging session
  gem 'pry-rails', '~> 0.3.9' # Use Pry as your rails console
  gem 'rspec-rails', '~> 6.0', '>= 6.0.3' # RSpec for Rails
end

group :development do
  gem "awesome_print", require:"ap" # Pretty print your Ruby objects with style -- in full color and with proper indentation
  gem 'better_errors', '~> 2.10', '>= 2.10.1' # Provides a better error page for Rails and other Rack apps
  gem 'binding_of_caller', '~> 1.0' # Retrieve the binding of a method's caller
  gem 'brakeman', '~> 6.0'# A static analysis security vulnerability scanner for Ruby on Rails applications
  gem 'i18n-tasks', '~> 1.0', '>= 1.0.12' # Manage translation and localization with static analysis, for Ruby i18n
  gem 'listen', '~> 3.8' # The Listen gem listens to file modifications and notifies you about the changes
  gem 'rails_best_practices', '~> 1.23', '>= 1.23.2' # A code metric tool for rails projects
  gem 'reek', '~> 6.1', '>= 6.1.4' # Code smell detector for Ruby
  gem 'rubocop-rails', '~> 2.20', '>= 2.20.2' # A RuboCop extension focused on enforcing Rails best practices and coding conventions
  gem 'rubocop-rootstrap', '~> 1.2' # Rootstrap's RuboCop configuration
  gem 'spring', '~> 4.1', '>= 4.1.1' # Rails application preloader
end

group :test do
  gem 'database_cleaner', '~> 2.0', '>= 2.0.2' # Strategies for cleaning databases in Ruby. Can be used to ensure a clean state for testing
  gem "capybara" # Acceptance test framework for web applications
  gem 'pg_query', '~> 4.2', '>= 4.2.1' # Ruby extension to parse, deparse, and normalize SQL queries using the PostgreSQL query parser
  gem 'prosopite', '~> 1.3', '>= 1.3.2' # A tool for finding slow SQL queries in Rails applications
  gem "selenium-webdriver" # Tool for writing automated tests of websites
  gem 'shoulda-matchers', '~> 5.3' # Making tests easy on the fingers and eyes
  gem 'simplecov', '~> 0.22.0' # Code coverage for Ruby 1.9+ with a powerful configuration library and automatic merging of coverage across test suites
  gem "webdrivers" # A collection of Ruby bindings for popular web drivers like Chrome, Firefox, PhantomJS, and more
  gem 'webmock', '~> 3.18', '>= 3.18.1' # Library for stubbing and setting expectations on HTTP requests in Ruby
end
