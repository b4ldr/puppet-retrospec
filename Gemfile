source 'http://rubygems.org'

gem 'awesome_print'
gem 'facets'
gem 'retrospec', '>= 0.6.1'
gem 'trollop'

group :development do
  gem 'pry'
  gem 'rdoc', '~> 3.12'
  gem 'overcommit'
end

group :test do
  gem 'bundler', '~> 1.0'
  gem 'fakefs', :require => 'fakefs/safe'
  gem 'json_pure', '= 2.0.1' # force this gem as 2.0.2 requires ruby > 2.0.0
  gem 'puppet', '4.10.8', :path => 'vendor/pup410'
  gem 'rake'
  gem 'facter'
  gem 'rspec', '~> 3.2'
  gem 'rubocop'
  gem 'yard', '~> 0.7'
  gem 'puppet-retrospec', :path => './'
end
