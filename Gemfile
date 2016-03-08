source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.10'

gem 'devise', '~> 3.4'
gem 'figaro', '1.0'
gem 'pundit', '~> 0.3'
gem 'whenever', :require => false
gem 'active_model_serializers'
gem 'haml-rails', '~> 0.9'
gem 'susy', '~> 2.2'
gem 'autoprefixer-rails'
gem 'data_migrate', '~> 1.2'

group :development, :test do
  gem 'rspec-rails', '3.1'
  gem 'capybara', '~> 2.5'
  gem 'pry'
end

# Use sqlite3 as the database for Active Record
group :production do
  gem 'pg', '~> 0.17'
  gem 'rails_12factor'
end

group :development do
  gem 'sqlite3', '~> 1.3'
end

group :test do
  gem 'poltergeist', '~> 1.8'
  gem 'factory_girl_rails', '~> 4.0'
  gem 'database_cleaner', '~> 1.3'
  gem 'shoulda-matchers', '~> 2.7'
  gem 'email_spec', '~> 1.6'
  gem 'timecop', '~>0.7'
end

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

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
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
