source 'http://rubygems.org'

gem 'rails', '3.1.3'
gem 'sqlite3'

gem 'jquery-rails'

group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end

unless ENV["CI"]
  # To use debugger
  gem 'ruby-debug19', :require => 'ruby-debug'
end

group :test, :development  do
  gem 'turn', '0.8.2', :require => false  
  gem "rails-erd"
end
