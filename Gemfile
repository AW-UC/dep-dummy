source 'http://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 4.2'

# Use postgresql as the database for Active Record
gem 'pg'

# Use rails-api
gem 'rails-api'

# Use device for authentification
gem 'devise'

# Support CORS
gem 'rack-cors'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Ember
gem 'active_model_serializers', '~> 0.8.3'

# Paypal
gem 'paypal-sdk-adaptivepayments'

# Gravatar
gem 'gravatarify', '~> 3.1.1'

# File uploads
gem 'carrierwave', github: 'carrierwaveuploader/carrierwave'
gem 'fog-aws'
gem 'file_validators'

# DotEnv
gem 'dotenv-rails', :groups => [:development, :test]

group :development do
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
  gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

# Cache
# gem 'redis'

# Debug
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'quiet_assets'
  gem 'bullet'

# Sample-User Creation
  gem 'ffaker'
  gem 'forgery'
  gem 'geocoder'

# Database dumps
  gem 'seed_dump'
end

# Tests
group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  # gem 'byebug'
  gem 'ruby-debug-ide'
  gem 'debase'

# Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console'

  # gem 'rspec-rails'
  # gem 'rb-readline'
  # gem 'childprocess'
  # gem 'spring'
  # gem 'spring-commands-rspec'
end

group :test do
	# gem 'selenium-webdriver'
	# gem 'capybara'
	# gem 'factory_girl_rails'
	# gem 'database_cleaner'
end

group :production do
  # Heroku
  gem 'rails_12factor'
end