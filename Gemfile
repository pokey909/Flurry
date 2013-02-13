source 'https://rubygems.org'

gem 'rails', '3.2.8'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'sqlite3'

# Gems used only for assets and not required
# in production environments by default.
gem 'sinatra', '1.3.2'

social_stream_gems = lambda {
  gem 'social_stream-base', '~> 1.1.0'
  gem 'social_stream-documents', '~> 1.1.0'
  gem 'social_stream-linkser', '~> 1.1.0'
  gem 'social_stream-ostatus', '~> 1.1.0'
}
git 'git://github.com/ging/social_stream.git', :branch => '1-0-stable', &social_stream_gems

# Force the first version of avatars_for_rails that does not collide with bootstrap
gem 'avatars_for_rails', '~> 0.2.6'
# Be able to pass tests
gem 'net-ssh', '=2.4.0'

# Shortener
gem 'shortener'

gem 'rubyzip', '=0.9.9'

group :test do
  # Pretty printed test output
  gem 'factory_girl', '~> 2.6'
  gem 'capybara'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :test, :development do
  gem 'turn'
  gem 'rspec-rails'
  gem 'capybara'
  gem 'guard-rspec'
end
gem 'jquery-rails'

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
