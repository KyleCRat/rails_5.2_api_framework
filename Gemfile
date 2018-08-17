source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

################################################################################
# Webserver
################################################################################

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.1'

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS)
gem 'rack-cors'

# Use Puma as the app server
gem 'puma', '~> 3.11'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

################################################################################
# Database && Storage
################################################################################

# Use Postgresql as the database for ActiveRecord
gem 'pg'

# Use Redis adapter to run Action Cable in production
gem 'redis', '~> 4.0'

# Elasticsearch search database
gem 'chewy'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

################################################################################
# Authentication
################################################################################

# devise authentication system
gem 'devise_token_auth'

# pundit authorization system
gem 'pundit'

# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'

################################################################################
# Application Structure
################################################################################

# Better enumerations in rails
gem 'enumerations'

# Service Objects and Service Object Chaining
gem 'interactor'

################################################################################
# Documentation
################################################################################

# Eaily view db schemas - bundle exec annotate
gem 'annotate', group: :development

################################################################################
# Error and Performance Logging
################################################################################

# Error and Performance monitoring
gem 'airbrake', '~> 7.1'
gem 'newrelic_rpm'

group :development, :test do
  # local debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]

  # define local variabes in development - config/
  gem 'figaro'

  # Preview email in the default browser instead of sending it via
  gem 'letter_opener'

  # A library for setting up Ruby objects as test data
  gem 'factory_bot'

  # A library for generating fake data
  gem 'faker'

  # Rspec testing library
  gem 'rspec-rails'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'

  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'

  #live reload for auto refresh of development
  gem 'guard-livereload', require: false
  gem 'rack-livereload'
end
