source 'https://rubygems.org'
ruby '2.0.0'

gem 'rails', '4.0.0'

group :development, :test do
  gem 'sqlite3'
  gem 'rspec-rails'
  gem 'guard-rspec', '2.5.0'
  gem 'spork-rails', github: 'sporkrb/spork-rails'
  gem 'guard-spork', '1.5.0'
  gem 'childprocess'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
end

gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jbuilder'

group :doc do
  gem 'sdoc', require: false
end

group :production do
  gem 'pg'
  gem 'rails_12factor'
end
