source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '7.1.0'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0', '>= 5.0.8'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2.2'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '>= 4.0.4'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '>= 2.5.4'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.1', '>= 2.1.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end


gem 'country_select'
gem 'devise', '>= 4.7.0'
gem 'fog-softlayer'
gem 'haml-rails', '>= 2.1.0'
gem 'json'
gem 'responders', '>= 3.0.0'
gem 'sidekiq'
gem 'simple_form', '>= 4.0.0'
group :development do
  gem 'better_errors', '>= 2.3.0'
  gem 'binding_of_caller'
  gem 'guard', require: false
  gem 'guard-rails', require: false
  gem 'guard-bundler', require: false
  gem 'guard-livereload', require: false
  gem 'guard-rspec', require: false
  gem 'jazz_fingers', '>= 2.0.0'
  gem 'letter_opener'
  gem 'listen', '~> 2.7.12'
  gem 'quiet_assets'
  gem 'spring-commands-rspec'
  gem 'thin'
end

group :development, :test do
  gem 'rspec-rails', '>= 3.5.0'
  gem 'shoulda-matchers', require: false
end

group :test do
  gem 'capybara'
  gem 'email_spec'
  gem 'turnip'
end
