source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.7.0"
gem "rails", "~> 7.0.4"
gem "sprockets-rails"
gem "sqlite3", "~> 1.4"
gem "puma", "~> 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem 'ransack'
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "bootsnap", require: false

# My Custom Gems
gem 'devise', '~> 4.8', '>= 4.8.1'
gem 'followability', github: 'nejdetkadir/followability', branch: 'main'
gem 'pagy'
gem "pg", "~> 1.1"


group :development, :test do
  gem "debug", platforms: %i[ mri mingw x64_mingw ]
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
end
gem "sassc-rails"
gem "redis", "~> 4.0"
gem "bootstrap_flash_messages", "~> 1.0.1"
