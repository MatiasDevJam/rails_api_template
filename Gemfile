# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.2.2'

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem 'rails', '~> 7.0.6'

gem 'activeadmin', '~> 2.9'
gem 'active_storage_base64', '~> 2.0.0'
gem 'arctic_admin', '~> 3.3.0'
gem 'aws-sdk-s3', '~> 1.75', require: false
gem 'bootsnap', '~> 1.4', '>= 1.4.5'
gem 'delayed_job_active_record', '~> 4.1', '>= 4.1.5'
gem 'devise', '~> 4.7', '>= 4.7.2'
gem 'jbuilder', '~> 2.10'
gem 'pagy', '~> 4.0'
gem 'pg', '~> 1.1', '>= 1.1.4'
gem 'puma', '~> 5.6'
gem 'pundit', '~> 2.1'
gem 'rack-cors', '~> 1.0', '>= 1.0.6'
gem 'rswag-api'
gem 'rswag-ui'
gem 'sass-rails', '~> 6.0.0'
gem 'sendgrid', '~> 1.2.4'
gem 'sprockets', '~> 3.7.2'
gem 'yaaf', '~> 2.2'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'
# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

group :development, :test do
  gem 'annotate', '~> 3.2', '>= 3.0.3'
  gem 'dotenv-rails', '~> 2.7.6'
  gem 'factory_bot_rails', '~> 5.1', '>= 5.1.1'
  gem 'pry-byebug', '~> 3.9', platform: :mri
  gem 'pry-rails', '~> 0.3.9'
  gem 'rspec-rails', '~> 4.1'
  gem 'rswag-specs'
end

group :development do
  gem 'better_errors', '~> 2.5', '>= 2.5.1'
  gem 'brakeman', '~> 5.1'
  gem 'letter_opener', '~> 1.7'
  gem 'listen', '~> 3.2'
  gem 'rails_best_practices', '~> 1.20'
  gem 'reek', '~> 6.1', '>= 6.1.1'
  gem 'rubocop-rails', '~> 2.20', '>= 2.20.2', require: false
  gem 'spring', '~> 4.0'
end

group :test do
  gem 'faker', '~> 2.13'
  gem 'shoulda-matchers', '~> 4.1', '>= 4.1.2'
  gem 'simplecov', '~> 0.13.0', require: false
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
