source 'https://rubygems.org'

ruby '~> 2.4'

gem 'rails', '~> 5.2.4'

gem 'sqlite3'
gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails'
gem 'jquery-rails'
gem 'turbolinks', github: 'rails/turbolinks'
# Pin Puma to a recent-ish version that supports OpenSSL, which is
# what the CircleCI environment has.
gem 'puma', '~> 4.3'

group :test do
  gem 'capybara', '~>3.32'
  gem 'selenium-webdriver'
  gem 'database_cleaner'
  gem 'percy-capybara', '~> 4.2.0'
end

group :production do
  gem 'rails_12factor'
end
