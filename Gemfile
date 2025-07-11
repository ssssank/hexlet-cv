# frozen_string_literal: true

ruby '3.2.2'

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gem 'acts-as-taggable-on'

gem 'ruby-openai'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
# NOTE Не обновил версию рельсы, т.к. https://github.com/charlotte-ruby/impressionist/issues/302
gem 'rails', '~> 7', '>= 7.1.0'
# Use Puma as the app server
gem 'puma'
# Use SCSS for stylesheets
# gem 'sass-rails'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '>= 2.12.0'
# Use Redis adapter to run Action Cable in production
gem 'redis'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

gem 'bootstrap', '>= 5.3.2'
gem 'jquery-rails', '>= 4.6.0'
gem 'sorbet'
gem 'sprockets-rails', '>= 3.5.0'
gem 'terser'
# Reduces boot times through caching; required in config/boot.rb
gem 'aasm'
gem 'active_form_model', '~> 0.5.1'
gem 'bootsnap', require: false
gem 'browser'
gem 'cocoon'
gem 'counter_culture', '>= 3.3.1'
gem 'devise', '>= 4.9.3'
gem 'devise-bootstrap-views'
gem 'devise-i18n', '>= 1.11.1'
gem 'dotenv-rails', '>= 3.0.0'
gem 'dry-container'
gem 'enumerize', '>= 2.7.0'
gem 'flash_rails_messages'
gem 'geocoder'
gem 'gon'
gem 'impressionist'
gem 'kaminari'
gem 'meta-tags', '>= 2.19.0'
gem 'net-imap', require: false
gem 'net-pop', require: false
gem 'net-smtp', require: false
gem 'nokogiri'
gem 'omniauth', '>= 2.1.2'
gem 'omniauth-github'
gem 'omniauth-rails_csrf_protection', '>= 1.0.2'
gem 'paint'
gem 'paper_trail', '>= 15.0.0'
gem 'pundit', '>= 2.3.1'
gem 'rails-i18n', '>= 7.0.7'
gem 'ransack', '>= 4.1.0'
gem 'recaptcha'
gem 'redcarpet', github: 'vmg/redcarpet'
gem 'sentry-rails', '>= 5.9.0'
gem 'sentry-ruby'
gem 'simple_form', '>= 5.3.0'
gem 'slim-rails', '>= 3.6.3'
gem 'translit'
gem 'validate_url'
gem 'valid_email2', '>= 5.0.0'
gem 'wicked_pdf', '>= 2.7.0'
gem 'wkhtmltopdf-binary'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'faker'
  # Use sqlite3 as the database for Active Record
  gem 'factory_bot_rails', '>= 6.3.0'
  gem 'rubocop-performance'
  gem 'rubocop-rails', '>= 2.19.0'
  gem 'slim_lint', '>= 0.25.0'
  gem 'sqlite3'
end

group :development do
  gem 'yard', '>= 0.9.29'
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'html2slim'
  gem 'i18n-debug'
  gem 'listen'
  gem 'web-console', '>= 4.2.1'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'reek'
  gem 'rubocop'
  gem 'solargraph', '>= 0.49.0'
  gem 'spring'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 3.39.1'
  gem 'minitest-power_assert'
  gem 'selenium-webdriver', '>= 4.9.0'
  gem 'simplecov', require: false
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers', '>= 5.3.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :production do
  gem 'pg'
end
