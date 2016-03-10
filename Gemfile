source 'https://rubygems.org'

ruby '2.2.3'

# Stack
gem 'rails', '4.2.4'
gem 'pg'
gem 'puma'
gem 'foreman'
gem 'grape'
gem 'hashie-forbidden_attributes'

# Views
gem 'slim-rails'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.1.0'
gem 'jquery-rails'
gem 'jquery-ui-rails'
gem 'jbuilder', '~> 2.0'
gem 'bootstrap-sass'
gem 'compass-rails', git: 'https://github.com/Compass/compass-rails', branch: 'master'
gem 'turbolinks'
gem 'sdoc', '~> 0.4.0', group: :doc
gem 'simple_form'
gem 'font-awesome-rails'

# Misc
gem 'exception_notification'
gem 'active_model_serializers'

group :development do
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'web-console', '~> 2.0'
  gem 'better_errors'
  gem 'pry'
  gem 'binding_of_caller'
end

group :test do
  gem 'factory_girl_rails'
  gem 'shoulda-matchers', require: false, github: 'thoughtbot/shoulda-matchers'
  gem 'capybara'
end

group :development, :test do
  gem 'rspec-rails'

  gem 'guard'
  gem 'guard-rspec'
  gem 'terminal-notifier-guard', require: false # Shows test alerts in OS X 10.8 Notification Center

  gem 'letter_opener'
end

# Logging
group :production, :staging do
  gem 'rails_12factor'
end
