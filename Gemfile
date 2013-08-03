source 'https://rubygems.org'

ruby '2.0.0'

gem 'rails', '4.0.0'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'


gem 'skylight'
gem 'git_hub_bub'
gem 'pg'
# gem 'ar_pg_array'
gem 'resque'
gem 'resque_def'
# gem 'sextant'
gem 'unicorn'
gem 'omniauth-github'
gem 'mail_view',          '~> 1.0.2'
gem 'will_paginate'
gem 'httparty'
gem 'dalli'
gem 'wicked'
gem 'rails_autolink'
gem 'bluecloth'
gem 'maildown'

gem 'rails_12factor', group: :production

gem 'rrrretry'

group :development do
  gem 'foreman'
  gem 'quiet_assets'
end

group :test do
  gem 'capybara'
  # Not essential but helpful for save_and_open_page
  gem 'launchy'
  gem 'webmock'
  gem 'vcr'
  gem 'mocha', require: false
  gem 'shoulda'
  gem 'simplecov', :require => false
end

group :development, :test do
  gem "teaspoon"
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 4.0.0'
  gem 'coffee-rails', '~> 4.0.0'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'

  gem 'uglifier', '>= 1.0.3'

  gem 'therubyracer'
  gem "less-rails"
end

gem 'jquery-rails'
gem 'devise',                  "~> 3.0.0.rc"
gem "twitter-bootstrap-rails", "~> 2.2.6"

gem "rack-timeout"


gem 'protected_attributes'


gem 'dotenv-rails', :groups => [:development, :test]
