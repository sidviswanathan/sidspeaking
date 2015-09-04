source 'https://rubygems.org'

# ruby '2.1.2'
gem 'rails', '~>4.1'
gem 'unicorn', '~> 4.7'

group :development do
  gem 'rails_best_practices'
  gem 'rack-mini-profiler'
  gem 'better_errors'
  gem 'pry', '0.10.1'
end

group :production do
  gem 'pg'
end

group :test, :development do
  gem 'pg'
end

group :test do
  gem 'database_cleaner'
  gem 'factory_girl_rails'
  gem 'rspec-rails', '>= 2.14'
end

# CSS / JS
gem 'sass-rails', '~> 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'compass-rails', '~> 1.1.7'
gem 'jquery-rails'
gem 'turbolinks'
gem 'foundation-rails', '5.4.3.1'
gem 'anjlab-bootstrap-rails', require: 'bootstrap-rails',
  github: 'anjlab/bootstrap-rails'

# Exception emails
gem 'exception_notification'

# Notifications
gem 'twilio-ruby'

# Backend
gem 'configatron', '~> 3.2.0'

# Queue
gem 'delayed_job_active_record'

# Users
gem 'devise', '~> 3.2'
gem 'omniauth-facebook', '2.0.0'

# Admin
gem 'rails_admin', '~> 0.6'

# AWS
gem 'aws-sdk', '< 2'

# Payments
gem 'stripe'

# Facebook data
gem 'koala', '1.10.1'

# Parsing Times
gem 'chronic'

# Video thumbnail
gem 'carrierwave'
gem 'streamio-ffmpeg'
gem "mini_magick"

# New Relic
gem 'newrelic_rpm'
gem 'ey_config'

# Custom logging
gem 'multi_logger'