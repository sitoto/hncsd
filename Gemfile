source 'https://rubygems.org'

gem 'rails', '3.2.9'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'mysql2'
gem 'thin'
gem 'rails-i18n'
gem 'spreadsheet'
gem 'mechanize'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'libv8'
  gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'

  gem "less-rails", "~> 2.2.6"
end
gem "twitter-bootstrap-rails", "~> 2.1.7"

gem 'jquery-rails'

# To use ActiveModel has_secure_password
gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
group :development do
  gem "magic_encoding"
end
group :development, :test do
  gem "factory_girl_rails", "~> 4.0"

  gem "guard-test", "~> 0.7.0"
  gem 'rb-inotify', :require => false
end

group :tool do
  gem "capistrano", "~> 2.13.5"
  gem "rvm-capistrano", "~> 1.2.7"
end
