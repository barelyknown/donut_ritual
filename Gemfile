source 'https://rubygems.org'
source 'https://rails-assets.org'
ruby "2.1.1"

gem 'rails', '4.1.0.rc2'
gem 'pg'
gem 'sass-rails', '~> 4.0.2'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.0.0'
gem 'jquery-rails'
gem 'turbolinks'
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'sdoc', '~> 0.4.0',          group: :doc

gem 'unicorn'
gem 'haml-rails'
gem 'neat'
gem 'simple_form'

# Assets
gem 'rails-assets-normalize-css'

group :development do
  gem 'refills', github: 'thoughtbot/refills'
  gem 'spring'
  gem 'quiet_assets'
  gem 'letter_opener'
  gem "spring-commands-rspec"
end

group :development, :test do
  gem 'minitest'
  gem 'rspec-rails', github: "rspec/rspec-rails", tag: "v3.0.0.beta2"
  gem 'capybara', '>= 2.2.0'
  gem 'factory_girl_rails'
  gem "better_errors"
  gem "binding_of_caller"
end

group :test do
  gem 'shoulda-matchers'
end

gem 'dotenv-rails', :groups => [:development, :test]
