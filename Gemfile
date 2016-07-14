source "https://rubygems.org"

# Declare your gem's dependencies in live_logs.gemspec.
# Bundler will treat runtime dependencies like base dependencies, and
# development dependencies will be added by default to the :development group.
gemspec

# Declare any dependencies that are still in development here instead of in
# your gemspec. These might include edge Rails or gems from your path or
# Git. Remember to move these dependencies to your gemspec before releasing
# your gem to rubygems.org.

gem 'passenger', '~> 5.0', '>= 5.0.29'
gem 'foundation-rails', '>5.0.0'
gem 'font-awesome-rails'
gem 'haml-rails'
gem 'sass-rails', '>= 4.0.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '>= 4.0.0'
gem 'haml_coffee_assets'

# Use jquery as the JavaScript library
gem  'jquery-rails'
gem  'marionette-rails', '< 2'
gem  'backbone-on-rails', '< 1'
gem  'high_voltage'

gem  'file-tail'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  
  # Mutes compiling assets in the log
  gem 'quiet_assets'
end
