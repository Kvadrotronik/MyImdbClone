source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.1.2"

gem "bootsnap"
gem "rails", "~> 7.0.4", ">= 7.0.4.1"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "jsbundling-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "cssbundling-rails"
gem "jbuilder"
gem "redis"
gem 'friendly_id', '~> 5.4.0'
gem 'devise'
gem 'kaminari'
gem 'bootstrap5-kaminari-views'
gem 'ransack'
gem 'simple_form'
gem 'webpacker'
gem 'sass-rails'

group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
  gem "rspec-rails"
  gem "factory_bot_rails"
  gem "faker"
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end

group :production do
  gem "pg", group: :production
  gem 'rails_12factor', group: :production
end
