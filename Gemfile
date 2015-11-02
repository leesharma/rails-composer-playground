source 'https://rubygems.org'
ruby '2.2.3'

gem 'rails', '4.2.4'
gem 'pg'
gem 'puma'

gem 'rails_12factor'
gem 'pry-rails'

# assets

gem 'sass-rails', '~> 5.0'
gem 'autoprefixer-rails'
gem 'bootstrap-sass'
gem 'bootstrap-material-design'

gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'high_voltage'

gem 'simple_form'

# api

gem 'jbuilder', '~> 2.0'

# auth

gem 'devise' # authentication
gem 'pundit' # authorization
gem 'upmin-admin' # basic admin panel

group :development do
  gem 'spring'
  gem 'spring-commands-rspec'

  gem 'better_errors'
  gem 'binding_of_caller'

  gem 'annotate', require: false
  gem 'brakeman', require: false
  gem 'mailcatcher', require: false

  gem 'guard-bundler'
  gem 'guard-rails'
  gem 'guard-rspec'

  gem 'quiet_assets'
  gem 'bullet'
  gem 'rails-footnotes'

  gem 'rb-fchange', require: false
  gem 'rb-fsevent', require: false
  gem 'rb-inotify', require: false
end

group :development, :test do
  gem 'factory_girl_rails'
  gem 'faker'
  gem 'awesome_print'
  gem 'pry-rescue'
  gem 'rspec-rails'
  gem 'rubocop'
  gem 'dotenv-rails'
end

group :test do
  gem 'capybara'
  gem 'database_cleaner'
  gem 'launchy'
  gem 'selenium-webdriver'
end
