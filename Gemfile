source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'


# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'
gem 'bootstrap-sass', '~> 3.0.2.0' # Twitter Bootstrap front-end framework
gem 'activesupport'

gem 'ruby-progressbar' #nice progressbar for seeding process
gem "gritter" #for better flash messages

#for nice icons
gem "font-awesome-rails"

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

group :production do
  gem 'pg' # Heroku database
  gem 'rails_12factor' # Heroku support
end

group :development do
  gem 'quiet_assets' # Turns off the Rails asset pipeline log
  gem "bullet", "~> 4.7.1" # Helps increase performance by alerting dev to reduce the number of queries app makes
    gem "better_errors"
    gem 'flay'
    gem 'annotate'
    gem 'lol_dba'
    gem 'rails_best_practices'
    gem 'smusher'
    gem 'reek'
    gem 'rack-mini-profiler'
    gem 'brakeman', :require => false
    gem 'rspec-rails' # Run rake tests in developmentgem 'sqlite3'
end

group :development, :test do
  # Use sqlite3 as the database for Active Record
  gem 'sqlite3'
end

group :test do
  gem 'selenium-webdriver'
  gem 'capybara'
  gem 'libnotify'
  gem 'factory_girl_rails'
end

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
