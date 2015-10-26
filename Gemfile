# A sample Gemfile
source "https://rubygems.org"

if ENV.key?('PUPPET_VERSION')
  puppetversion = "= #{ENV['PUPPET_VERSION']}"
else
  puppetversion = ['= 3.6.1']
end

gem 'rspec'
gem 'rspec-puppet'
gem 'puppet', puppetversion
gem 'fuubar'
gem 'librarian-puppet'
gem 'rake'
