#
source 'https://rubygems.org'

gem 'rails', '4.2.6'
gem 'rails-api', '~>0.4', '>=0.4.0'
# Alternate Rails shell.
gem 'pry-rails', '~>0.3', '>=0.3.4'
# This gem supports cross origin request handling.
gem 'rack-cors', '~>0.4', '>=0.4.0', :require => 'rack/cors'

gem 'jbuilder', '~> 2.0', '>=2.6.0'

group :development do
  gem 'spring', '~>2.0', '>=2.0.0'
end

group :development, :test do
  gem 'tzinfo-data', :platforms=>[:mingw, :mswin, :x64_mingw, :jruby]
  gem 'httparty', '~>0.14', '>=0.14.0'

  gem 'rspec-rails', '~> 3.5', '>=3.5.2'
  gem 'byebug', '~>9.0', '>=9.0.6'
  # Automatically drops into pry shell when byebug triggered (binding-pry).
  gem 'pry-byebug', '~>3.4', '>=3.4.0'
end

group :production do
  gem 'rails_12factor', '~>0.0', '>= 0.0.3'
  gem 'puma', '~>3.6', '>=3.6.0', :platforms=>:ruby
end

gem 'pg', '~>0.19', '>=0.19.0'
gem 'mongoid', '~>5.1', '>=5.1.5'
