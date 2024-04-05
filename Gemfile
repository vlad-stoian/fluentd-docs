source 'https://rubygems.org'

# https://devcenter.heroku.com/articles/ruby-versions
ruby '2.4.1'

gem 'sinatra', '2.0.0'
gem 'sinatra-asset-pipeline', '~> 2.0', '>= 2.0.0'
gem 'rdiscount', '~> 2.2.0'
gem 'rest-client', '1.2.0'
gem 'sass'
gem 'haml'
gem 'coderay'
gem 'rack-codehighlighter', '>= 0.6.0'
gem 'sanitize', '>= 4.6.1'
gem 'jemalloc', '~> 1.0.1'
gem 'minitest'

# Compressor
gem 'yui-compressor', :require => 'yui/compressor'

# Webserver
gem 'unicorn', '~> 5.4.0'
gem 'unicorn-worker-killer', '~> 0.4.4'

# Addons
gem 'newrelic_rpm', '~> 3.18.1'
gem 'airbrake', '~> 3.1.5'

# Dev
group :development do
  gem 'rake'
  gem 'rack-test', '>= 0.7.0'
  gem 'shotgun', '~> 0.9'
end

# Production
group :production do
  gem 'rack-cache', '>= 1.7.2'
  gem 'dalli', '~> 2.1.0'
end
