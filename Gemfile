source 'https://rubygems.org'

# Specify your gem's dependencies in interpol.gemspec
gemspec

group :extras do
  gem 'debugger' if defined?(RUBY_ENGINE) && RUBY_ENGINE == 'ruby' && RUBY_VERSION == '1.9.3'
  gem 'ruby-debug', :platform => :mri_18
end

gem 'json-jruby', :platform => 'jruby'
gem 'compass_twitter_bootstrap', :git => 'git://github.com/vwall/compass-twitter-bootstrap.git'

gem 'json', :platform => 'ruby_18'

gem 'sinatra', '>= 1.3.2', '< 2.0.0'

gem 'cane', '~> 2.0', :platform => 'ruby_19'

