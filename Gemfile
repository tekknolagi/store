source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.5.0.dev'


gem 'rails', '~> 8'

gem 'pg', '~> 1.5', '>= 1.5.9'

gem 'puma', '~> 6.6'
gem 'jbuilder', '~> 2.13'

gem 'oj', '~> 3.16'
gem 'active_interaction', '~> 5.5'

# disable warnings
gem 'mutex_m'
gem 'bigdecimal'
gem 'drb'
gem 'base64'
gem 'observer'
gem 'benchmark'
gem 'reline'

# Kafka
gem 'ruby-kafka', '~> 1.5'
gem 'avro', '~> 1.9'
gem 'avro_turf'
gem 'extlz4', '~> 0.3.2', require: false
gem 'karafka', '~> 2.2.7'

# Monitoring
gem 'elastic-apm', '~> 4.7'
gem 'lograge'

gem 'vernier', '~> 1.5'
gem 'stackprof', '0.2.27'
gem 'sentry-ruby', '~> 5.22'
gem 'sentry-rails', '~> 5.22'

gem 'concurrent-ruby'

gem 'faraday', '~> 2.12.2'

# Storages
gem 'redis', '~> 5.3'

group :development, :test do
  gem 'bundler-audit', '~> 0.9.2'
  gem 'brakeman', '~> 7', require: false
  gem 'pry-byebug'
end

gem "bootsnap"
