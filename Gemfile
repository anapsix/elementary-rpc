source 'https://rubygems.org'

# Specify your gem's dependencies in elementary-rpc.gemspec
gemspec

gem 'protobuffy', :github => 'lookout/protobuffy'

if RUBY_VERSION.to_f < 2.2.2
  gem 'rack', '< 2.0.0'
  gem 'activesupport', '< 5.0.0'
else
  gem 'rack'
  gem 'activesupport'
end

group :test do
  gem 'rspec'
end

group :development do
  gem 'pry'
  gem 'debugger', :platform => :mri_19
  gem 'debugger-pry', :platform => :mri_19
  gem 'byebug', :platform => [:mri_20, :mri_21]
end
