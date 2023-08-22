source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"

gem 'rails'
gem 'image_processing'
gem 'mini_magick'
gem 'active_storage_validations'
gem 'bcrypt'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'
gem 'bootstrap-sass'
gem 'puma'
gem 'sassc-rails'
gem 'jbuilder'
gem 'bootsnap', require: false
gem 'factory_bot'
gem 'factory_bot_rails'
gem 'jsbundling-rails'
gem 'stimulus-rails'
gem 'turbo-rails'
gem 'sprockets-rails'
gem "importmap-rails", "~> 1.2"

group :development, :test do
  # gem 'debase'
  # gem 'ruby-debug-ide'
  gem 'rspec-rails'
  gem 'simplecov'
  gem 'sqlite3'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end
group :development do
  gem 'web-console'
  gem 'rack-mini-profiler'
  gem 'listen'
  gem 'spring'
end
group :test do
  gem 'capybara'
  gem 'selenium-webdriver'
  gem 'webdrivers'
  gem 'rails-controller-testing'
  gem 'minitest'
  gem 'guard'
  gem 'guard-minitest'
end
group :production do
  gem 'pg'
  gem 'aws-sdk-s3', require: false
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

