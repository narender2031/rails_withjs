source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
ruby '2.5.1'
# Rails
gem 'rails', '~> 5.2.1'

# Pume 
gem 'puma', '~> 3.11'

# Sass-rails 
gem 'sass-rails', '~> 5.0'

# uglifier
gem 'uglifier', '>= 1.3.0'

# Coffe script
gem 'coffee-rails', '~> 4.2'

# turbo links
gem 'turbolinks', '~> 5'

# JSON Token 
gem 'jwt'

# background JObs
gem 'que', '~> 1.0.0.beta3'


gem 'jbuilder', '~> 2.5'

# Bruadcramps
gem 'loaf', '0.6.2'

# validate phone number
gem 'phonelib', '0.6.21'

# javascripts
gem 'webpacker', '~> 3.4'

# Icons
gem 'font-awesome-sass', '~> 5.0.9'

# Forms
gem 'simple_form', '4.0.0'

# bootstrap 
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# bootstrap version 4
gem 'bootstrap', '~> 4.0.0'

# user authantication
gem 'devise'

# add static page
gem 'high_voltage'

# database
gem 'pg'

# policy and validations
gem 'pundit'

# frontend frameworks
gem 'slim', '3.0.9'

# assest pipeline
gem 'chosen-rails', '1.8.3'

# Better Emails
gem 'bootstrap-email', '0.2.3'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

# soft delete 
gem "paranoia", "~> 2.2"

# Meta tags
gem 'meta-tags', '2.10.0'

# SEO stuff
gem 'friendly_id', '~> 5.1.0'

# jquery 
gem 'jquery-rails'

group :development do
  # for better rails error
  gem 'better_errors'

  # deploy code to production
  gem 'capistrano', '~> 3.0.1'
  gem 'capistrano-bundler'
  gem 'capistrano-rails', '~> 1.1.0'
  gem 'capistrano-rails-console'
  gem 'capistrano-rvm', '~> 0.1.1'

  # file version handle all file chnages
  gem 'guard-bundler'
  gem 'guard-rails'

  # enviorment variables
  gem 'dotenv-rails', '2.4.0'
  
  gem 'guard-rspec'
  gem 'hub', :require=>nil
  gem 'rails_layout'
  gem 'rb-fchange', :require=>false
  gem 'rb-fsevent', :require=>false
  gem 'rb-inotify', :require=>false
  gem 'spring-commands-rspec'
end
group :development, :test do
  gem 'factory_bot_rails'
  gem 'faker'
  gem 'rspec-rails'
end
group :test do
  gem 'database_cleaner'
  gem 'launchy'
end
