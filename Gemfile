source "https://rubygems.org"

ruby "3.2.3"

gem "rack-canonical-host"
gem "good_migrations"
gem "vite_rails", "~> 3.0"
gem "rails", "~> 7.1.3", ">= 7.1.3.4"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "redis", ">= 4.0.1"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "bootsnap", require: false

group :development, :test do
  gem "factory_bot_rails"
  gem "dotenv", ">= 3.0"
  gem "rspec-rails"
  gem "debug", platforms: %i[ mri windows ]
end

group :development do
  gem "letter_opener"
  gem "erb_lint", require: false
  gem "bundler-audit", require: false
  gem "brakeman", require: false
  gem "annotate"
  gem "web-console"
end

group :test do
  gem "selenium-webdriver", require: false
  gem "capybara", require: false
end
