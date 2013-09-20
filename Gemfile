source 'http://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.0.0'

gem 'pg'

gem 'sass-rails', '4.0.0'
gem 'coffee-rails', '4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

gem 'bcrypt-ruby', '~> 3.0.0'
gem 'factory_girl_rails', '4.2.1'

group :development, :test do
  gem 'rspec-rails', '2.13.1'
  gem 'guard-rspec', '2.5.0'
  gem 'spork-rails', github: 'railstutorial/spork-rails'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
end

gem 'uglifier', '2.1.1'

gem 'bootstrap-sass'

gem 'sprockets'

require 'rbconfig'
gem 'wdm', '>= 0.1.0' if RbConfig::CONFIG['target_os'] =~ /mswin|mingw/i

group :doc do
  gem 'sdoc', '0.3.20', require: false
end