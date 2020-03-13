source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "2.6.5"

# Essentials
gem "bootsnap", ">= 1.4.2", require: false
gem "jbuilder", "~> 2.7"
gem "puma", "~> 4.1"
gem "rails", "~> 6.0.2", ">= 6.0.2.1"

# Frontend
gem "sass-rails", ">= 6"
gem "turbolinks", "~> 5"
gem "webpacker", "~> 4.0"

# Backend
gem "sidekiq"

# Database Related
gem "activerecord-import"
gem 'sqlite3', '~> 1.4'

group :development, :test do
  # Call "byebug" anywhere in the code to stop execution and get a debugger console
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling "console" anywhere in the code.
  gem "awesome_print"
  gem "listen", ">= 3.0.5", "< 3.2"
  gem "web-console", ">= 3.3.0"
end

group :test do
  gem "byebug", platforms: [:mri, :mingw, :x64_mingw]
  gem "database_cleaner"
  gem "factory_bot_rails"
  gem "ffaker"
  gem "pry"
  gem "pry-byebug"
  gem "rspec-rails"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
