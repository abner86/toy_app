source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0.rc3'
# Use mysql as the database for Active Record
gem 'mysql2'
# Use SCSS for stylesheets
gem 'sass-rails', '5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '2.6.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '4.1.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails', '4.0.1'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', '2.5.3'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '2.2.5'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '0.4.1', group: :doc

gem 'bootstrap-sass', '3.3.1.0'

# Use ActiveModel has_secure_password
 gem 'bcrypt', '3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', '3.5.1'

  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '2.0.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '1.2.0'
  gem 'capistrano', '3.3.5'
end

group :test do
  gem 'minitest-reporters', '1.0.8'
  gem 'mini_backtrace', '0.1.3'
  gem 'guard-minitest', '2.3.2'
end

group :production do
	gem 'pg', '0.17.1'
	gem 'rails_12factor', '0.0.3'
  gem 'unicorn', '4.8.3'
end