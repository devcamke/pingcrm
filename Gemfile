source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '~> 3.1'

# Full-stack web application framework. (https://rubyonrails.org)
gem 'rails'

# Pg is the Ruby interface to the {PostgreSQL RDBMS}[http://www.postgresql.org/] (https://github.com/ged/ruby-pg)
gem 'pg'

# Puma is a simple, fast, threaded, and highly concurrent HTTP 1.1 server for Ruby/Rack applications (https://puma.io)
gem 'puma', '~> 5.0'

# Use webpack to manage app-like JavaScript modules in Rails (https://github.com/rails/webpacker)
gem 'webpacker', '6.0.0.rc.6'

# Create JSON structures via a Builder-style DSL (https://github.com/rails/jbuilder)
gem 'jbuilder'

# High-level wrapper for processing images for the web with ImageMagick or libvips. (https://github.com/janko/image_processing)
gem 'image_processing', '~> 1.2'

# Boot large ruby/rails apps faster (https://github.com/Shopify/bootsnap)
gem 'bootsnap', require: false

group :development, :test do
  # See https://guides.rubyonrails.org/debugging_rails_applications.html#debugging-with-the-debug-gem
  gem "debug", platforms: [:mri, :mingw, :x64_mingw]

  # Automatic Ruby code style checking tool. (https://github.com/rubocop-hq/rubocop)
  gem 'rubocop', require: false

  # Automatic performance checking tool for Ruby code. (https://github.com/rubocop-hq/rubocop-performance)
  gem 'rubocop-performance', require: false

  # Automatic Rails code style checking tool. (https://github.com/rubocop-hq/rubocop-rails)
  gem 'rubocop-rails', require: false

  # factory_bot_rails provides integration between factory_bot and rails 5.0 or newer (https://github.com/thoughtbot/factory_bot_rails)
  gem 'factory_bot_rails'
end

group :development do
  # A debugging tool for your Ruby on Rails applications. (https://github.com/rails/web-console)
  gem 'web-console'

  # Profiles loading speed for rack applications. (https://miniprofiler.com)
  gem 'rack-mini-profiler'

  # Rails application preloader (https://github.com/rails/spring)
  gem 'spring'

  # Brings Rails named routes to javascript (http://github.com/railsware/js-routes)
  gem 'js-routes', require: false
end

group :test do
  # Capybara aims to simplify the process of integration testing Rack applications, such as Rails, Sinatra or Merb (https://github.com/teamcapybara/capybara)
  gem 'capybara'

  # The next generation developer focused tool for automated testing of webapps (https://github.com/SeleniumHQ/selenium)
  gem 'selenium-webdriver'

  # Easy download and use of browser drivers. (https://github.com/titusfortner/webdrivers)
  gem 'webdrivers'
end

# Timezone Data for TZInfo (https://tzinfo.github.io)
gem 'tzinfo-data'

# Inertia adapter for Rails (https://github.com/inertiajs/inertia-rails)
gem 'inertia_rails', '>= 1.2.2'

# Easily generate fake data (https://github.com/faker-ruby/faker)
gem 'faker', require: false

# The Ultimate Pagination Ruby Gem (https://github.com/ddnexus/pagy)
gem 'pagy'

# Flexible authentication solution for Rails with Warden (https://github.com/heartcombo/devise)
gem 'devise'

# A fast JSON parser and serializer. (http://www.ohler.com/oj)
gem 'oj'

# Simple authorization solution for Rails. (https://github.com/CanCanCommunity/cancancan)
gem 'cancancan'
