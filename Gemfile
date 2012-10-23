source 'https://rubygems.org'

gem 'rails', '3.2.8'

gem 'carrierwave'
gem 'fog'
gem 'jquery-rails'
gem 'rmagick', :require => "RMagick"

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'coffee-rails', '~> 3.2.1'
  gem 'sass-rails',   '~> 3.2.3'
  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'heroku'
  gem 'sqlite3'
end

group :development, :test do
  gem 'rspec-rails'
end

group :production do
  gem 'pg'
  gem 'thin'
end

group :test do
  gem 'database_cleaner'
end
