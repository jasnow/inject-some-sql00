source 'https://rubygems.org'

gem 'rails', '4.2.9.rc2'
gem 'protected_attributes' # For Rails 4.
gem 'rails-perftest' # Need for Rails 4+.
gem 'ruby-prof', '0.15.9' # Need for Rails 4+. # LOCKED DOWN

gem 'jquery-rails'
gem 'coderay'
gem 'rdiscount'
gem 'test-unit'

# Gems used only for assets and not required
#    in production environments by default.
group :assets do
  gem 'sass-rails'
  gem 'coffee-rails'

  # See https://github.com/sstephenson/execjs#readme for more
  #    supported runtimes
  gem 'therubyracer', :platforms => :ruby

  gem 'twitter-bootstrap-rails'
  gem 'less-rails', git: 'https://github.com/MustafaZain/less-rails' # LOCKED DOWN
  gem 'uglifier'
end

group :development do
  gem 'sqlite3'
end

group :production do
  gem "pg"
end

######################################################################
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
