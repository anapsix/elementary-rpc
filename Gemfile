source 'https://rubygems.org'

# Specify your gem's dependencies in elementary-rpc.gemspec
gemspec :name => 'elementary-rpc'

gem 'protobuffy', :github => 'lookout/protobuffy'

group :test do
  gem 'rspec'
end

group :development do
  gem 'pry'
  gem 'debugger', :platform => :mri_19
  gem 'debugger-pry', :platform => :mri_19
  gem 'byebug', :platform => [:mri_20, :mri_21]
end

# added to make travis ci happy
gem "bundler", "~> 1.6"
gem "rake", "10.5.0"
gem 'concurrent-ruby', '>= 0.7'
gem 'faraday', '~> 0.9.0'
gem 'net-http-persistent', '~> 2.9.4'
gem 'lookout-statsd', '~> 2.0.0'
gem 'hashie'