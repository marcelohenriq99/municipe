source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.7'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.6'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby
gem 'jquery-rails'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# simple form rails
gem 'simple_form', '~> 5.1.0'
# cpf cnpj utils for generate and valid
gem 'cpf_cnpj', '~> 0.5.0'
# adding decorators
gem 'draper', '~> 4.0.2'
# adding file upload
gem 'carrierwave', '~> 2.0'
# adding search features
gem 'ransack', '~> 2.4.2'
# paginating 
gem 'kaminari', '~> 1.2'
# using enums
gem 'enumerate_it', '~> 3.2'
# auth with devise
gem 'devise', '~> 4.8'
# adding storages integration
gem 'fog-aws', '~> 3.10'
# jobs async with sidekiq
# gem 'sidekiq', '~> 6.2'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

group :development, :test do
  gem 'pry-rails', '~> 0.3.9'
  #tests gems
  gem 'rspec-rails', '~> 5.0.0'
  gem 'simplecov', '~> 0.21.2'
  gem 'ffaker', '~> 2.18.0'
  gem 'factory_bot_rails', '~> 6.2.0'
  gem 'shoulda-matchers', '~> 5.0.0'
  gem 'rails-controller-testing', '~> 0.0.3'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
