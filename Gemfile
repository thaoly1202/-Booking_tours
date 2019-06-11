# frozen_string_literal: true

source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }
ruby "2.5.5"

gem "bcrypt"
gem "bootsnap", ">= 1.1.0", require: false
gem "bootstrap-sass", "3.3.7"
gem "bootstrap-will_paginate", "1.0.0"
gem "carrierwave"
gem "coffee-rails", "~> 4.2"
gem "config"
gem "faker"
gem "figaro"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "mini_magick"
gem "puma", "~> 3.11"
gem "rails", "~> 6.0.0.rc1"
gem "rails-controller-testing"
gem "rubocop", "~> 0.54.0", require: false
gem "sass-rails", "~> 5.0"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"
gem "will_paginate", "3.1.7"

group :development, :test do
  gem "byebug", platforms: %i[mri mingw x64_mingw]
  gem "mysql2"
end

group :development do
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "capybara", ">= 2.15"
  gem "selenium-webdriver"
  gem "webdrivers"
end
gem "tzinfo-data", platforms: %i[mingw mswin x64_mingw jruby]
