# frozen_string_literal: true

source "https://rubygems.org"

ruby "3.2.3"

gem "bootsnap", require: false
gem "good_migrations"
gem "jbuilder"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "rack-canonical-host"
gem "rails", "~> 7.1.3", ">= 7.1.3.4"
gem "redis", ">= 4.0.1"
gem "stimulus-rails"
gem "turbo-rails"
gem "tzinfo-data", platforms: %i[windows jruby]
gem "vite_rails", "~> 3.0"

group :development, :test do
  gem "debug", platforms: %i[mri windows]
  gem "dotenv", ">= 3.0"
  gem "factory_bot_rails"
  gem "rspec-rails"
end

group :development do
  gem "annotate"
  gem "brakeman", require: false
  gem "bundler-audit", require: false
  gem "erb_lint", require: false
  gem "letter_opener"
  gem "rack-mini-profiler"
  gem "rubocop", require: false
  gem "rubocop-capybara", require: false
  gem "rubocop-factory_bot", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", ">= 2.22.0", require: false
  gem "web-console"
end

group :test do
  gem "capybara", require: false
  gem "selenium-webdriver", require: false
  gem "shoulda-matchers"
  gem "vcr"
  gem "webmock"
end
