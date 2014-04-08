source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.0.2'

# Postgre SQL info
# 1. PG creates errors on OSX so use this
#    ARCHFLAGS=-Wno-error=unused-command-line-argument-hard-error-in-future gem install pg
# 2. Start postgre server
# 3. Create socket connection and symlink
#     ls -l /tmp/.s.PGSQL.5432
#     grep unix_socket /usr/local/var/postgres/postgresql.conf
# 4. Create dir
#     sudo mkdir /var/pgsql_socket/
#     sudo ln -s /tmp/.s.PGSQL.5432 /var/pgsql_socket/
# 5. Create dbs
#    rake db:create:all
gem 'pg'

# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.0'

# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'

# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'

# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'

# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'

# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 1.2'

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

# Heroku GEMS
gem 'rails_12factor', group: :production



# Use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.1.2'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]
