source "http://rubygems.org"

group :test do
  gem "rake", '< 11'
  gem "puppet", ENV['PUPPET_VERSION'] || '~> 4'
  gem "puppet-lint"
  gem "rspec", "~> 3.1.0"
  gem "rspec-puppet"
  gem "puppet-syntax"
  gem "puppetlabs_spec_helper"
end

group :development do
  gem "travis"
  gem "travis-lint"
  gem "vagrant-wrapper"
  gem "puppet-blacksmith"
  gem "guard-rake"
end

group :system_tests do
  gem 'beaker-rspec', :require => false
  gem 'serverspec', :require => false
end
