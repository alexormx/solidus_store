source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "rails",          "7.0.4"
gem "solidus"
gem "sassc-rails",     "2.1.2"
gem "sprockets-rails", "3.4.2"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder",        "2.11.5"
gem "puma",            "5.6.4"
gem "bootsnap",        "1.12.0", require: false
gem "bulma-rails", "~> 0.9.4"
gem "active_storage_validations", "0.9.8"
gem "image_processing",           "1.12.2"
gem 'rails-i18n'
gem 'dotenv-rails', groups: [:development, :test]

group :development, :test do
  gem "sqlite3", "1.4.2"
  gem "debug",   "1.5.0", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console", "4.2.0"
end

group :test do
  gem "capybara",                 "3.37.1"
  gem "selenium-webdriver",       "4.2.0"
  gem "webdrivers",               "5.0.0"
  gem "minitest",                 "5.15.0"
  gem "minitest-reporters", group: :test
  gem "guard",                    "2.18.0"
  gem "guard-minitest",           "2.4.6"
end

group :production do
  gem "pg", "1.3.5"
  gem "aws-sdk-s3", require: false
end



gem "solidus_auth_devise", "~> 2.5"
gem "responders"
gem "canonical-rails"
gem "solidus_support"
gem "truncate_html"
gem "view_component", "~> 3.0"
gem "tailwindcss-rails"

group :test do
  gem "capybara-screenshot", "~> 1.0"
  gem "database_cleaner", "~> 2.0"
end

group :development, :test do
  gem "rspec-rails"
  gem "rails-controller-testing", "~> 1.0.5"
  gem "rspec-activemodel-mocks", "~> 1.1.0"
  gem "factory_bot", ">= 4.8"
  gem "factory_bot_rails"
  gem "ffaker", "~> 2.13"
  gem "rubocop", "~> 1.0"
  gem "rubocop-performance", "~> 1.5"
  gem "rubocop-rails", "~> 2.3"
  gem "rubocop-rspec", "~> 2.0"
end
