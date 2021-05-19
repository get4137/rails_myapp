# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

gem 'bootsnap', '>= 1.1.0', require: false
gem 'cancancan'
gem 'cocoon'
gem 'coffee-rails', '~> 4.2'
gem 'devise'
gem 'haml'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'materialize-sass'
gem 'pg'
gem 'puma', '~> 4.3'
gem 'rails', '~> 5.2.3'
gem 'rolify'
gem 'sass-rails'
gem 'turbolinks'
gem 'uglifier'

group :development, :test do
  gem 'pry'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'listen'
  gem 'web-console'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
