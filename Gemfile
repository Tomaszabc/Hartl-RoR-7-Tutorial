source "https://rubygems.org"
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby "3.2.2"
gem "rails"
gem "bootstrap-sass", "3.4.1"
gem "sassc-rails", "2.1.2"
gem "sprockets-rails", "3.4.2"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "puma"
gem "bootsnap", require: false



group :development, :test do
  gem 'sqlite3', '~> 1.4'
gem "debug", platforms: %i[ mri mingw x64_mingw ]
end
group :development do
  gem "web-console"
end
group :test do
  gem "capybara"
  gem "selenium-webdriver"
  gem "webdrivers"
  gem "rails-controller-testing"
  gem "minitest"
  gem "minitest-reporters"
  gem "guard"
  gem "guard-minitest"
end
group :production do 
   gem "pg"
end

gem "bcrypt"