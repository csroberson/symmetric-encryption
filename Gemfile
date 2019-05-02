source 'https://rubygems.org'

gemspec

gem 'activerecord', '~> 4.2'

gem 'appraisal'
gem 'awesome_print'
gem 'minitest'
gem 'minitest-stub_any_instance'
gem 'rake'

# Optional gem used by rake task for user to enter text to be encrypted
gem 'highline'

gem 'activerecord-jdbcsqlite3-adapter', platform: :jruby
gem 'jdbc-sqlite3', platform: :jruby
gem 'sqlite3', '~> 1.3.0', platform: :ruby

# Soft dependency, only required when storing encryption keys in AWS KMS
gem 'aws-sdk-kms'

gem 'google-cloud-kms'
gem 'google-protobuf', '~> 3.7', platform: :ruby

group :development do
  gem 'rubocop'
end
