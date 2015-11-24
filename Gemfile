source 'https://rubygems.org'


# Many gems kept from original Gemfile, some added from Tutorial http://bit.ly/1TaecRg


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.0'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .coffee assets and views
# gem 'coffee-rails', '~> 4.1.0'

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# SASS, Compass, Bootstrap, Fonticons
gem 'bootstrap-sass', '~> 3.2.0'
gem 'compass'
gem 'font-awesome-rails'
# gem 'autoprefixer-rails'


group :development do
  gem 'better_errors' # better error page
  gem 'letter_opener' # open a preview in the browser instead of sending mail
  gem 'guard' # CLI to easily handle events on file system modifications
  gem 'guard-rspec', '~> 4.2.8' # automatically run your specs (much like autotest)
end


group :development, :test do
  gem 'spring'

  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  # gem 'byebug'

  # Access an IRB console on exception pages or by using <%= console %> in views
  # gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
end


group :production do
  gem 'rails_12factor'
  gem 'puma', '2.11.1' # recommended by Heroku (alt. to Unicorn/Passenger)
end


gem 'pg' # Postgres (Dev/Test/Prod)

gem 'devise'
gem 'carrierwave'
gem 'friendly_id', '~> 5.0.0' # slugging and permalinks
gem 'will_paginate', '~> 3.0.6'

# gem 'public_activity' # actions performed by your users, like adding comments, responding etc
# gem 'acts_as_votable', '~> 0.10.0' # allowing records to be votable (e.g. Likes)
# gem 'acts_as_commentable'

gem 'acts_as_follower' # allow any model to follow any other model
gem 'counter_culture', '~> 0.1.33' # turbo-charged counter caches etc.

gem 'faker'
gem 'populator'
gem 'auto_html' # transforms URIs and includes the destination resource (YT etc.)

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development
