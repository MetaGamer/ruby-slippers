source 'https://rubygems.org'

ruby '1.9.3'

gem 'rails', '3.2.13'

#downgrade to avoid bug in 0.3.7
gem 'childprocess', '0.3.6'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.11.0'
  gem 'guard-rspec', '1.2.1'
  gem 'guard-spork', '1.2.0'
  gem 'spork', '0.9.2'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

gem 'jquery-rails', '2.0.2'

#need this for javascript
gem "therubyracer", :require => 'v8'

group :test do
  gem 'capybara', '1.1.2'
  gem 'rb-inotify', '~> 0.9'
  gem 'libnotify', '0.5.9'
end

group :production do
  gem 'pg', '0.12.2'
end

