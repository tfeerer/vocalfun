source 'http://rubygems.org'

gem 'rails', '3.1.3'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'


gem 'gravatar_image_tag', '0.1.0'
gem 'annotate', :git => 'git://github.com/jeremyolliver/annotate_models.git', :branch => 'rake_compatibility'
gem 'jquery-rails'

# Gems used only for assets and not required
# in production environments by default.

group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end


# gems specifically for Heroku go here
group :production do
# gem install activerecord-postgresql-adapter, didn't work, used the following instead
  gem "pg"
end

group :development, :test do
	gem 'rspec-rails', '2.6.1.beta1'
	gem 'sqlite3'
	gem 'webrat', '0.7.1'
	gem 'factory_girl_rails', '1.0'
	
end

# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

