source 'https://nexus.vinted.net/repository/rubygems-proxy-repos-group/'
private_gem_source = 'https://nexus.vinted.net/repository/rubygems-hosted-repos-group/'

# bootsnap is first in the Gemfile to maximize its effect
# it works best when it is required first before everything else
gem 'bootsnap', require: false
gem 'dotenv-rails', require: 'dotenv/rails-now'

gem 'rails', '~> 6.1.4', '>= 6.1.4.7'

gem 'mysql2', '~> 0.5.2'
gem 'rest-client', '~> 2.0.2'
gem 'memcached_store'
gem 'request_local_cache', '~> 0.3.0'
gem 'maxminddb', '0.1.22'
gem 'prawn', '0.13.2'
gem 'rack-attack', '~> 6.3'
gem 'builder', '~> 3.2.0'
gem 'rake'
gem 'rack', '~> 2.2'
gem 'nokogiri', '~> 1.13'
gem 'stringex', '1.5.1' # 2.x.x has performance issues
gem 'marginalia'
gem 'hexapdf', '~> 0.11.9'

gem 'libxml-ruby', require: 'xml'
gem 'mime-types'
gem 'friendlyfashion-rails_autolink', '~> 1.0.13', require: 'rails_autolink'
gem 'jquery-rails'
gem 'date_validator', '~> 0.8.0'
gem 'faraday-http-cache'
gem 'react_on_rails', '12.2.0'
gem 'webpacker', '~> 5.1.1'
gem 'http_accept_language', '~> 2.1', '>= 2.1.1'

gem 'fcm'
gem 'apnotic'
gem 'ddtrace'
gem 'geocoder', '~> 1.4'
gem 'google-protobuf'
gem 'useragent', '~> 0.10'
gem 'unicorn', '~> 4.9.0', require: false
gem 'liquid', '~> 4.0.3'
gem 'pbkdf2-ruby', require: 'pbkdf2'
gem 'statsd-ruby', '1.3.0', require: 'statsd'
gem 'oj'
gem 'redis', '~> 4.5.0'
gem 'hiredis', '~> 0.6'
gem 'redis-namespace', '~> 1.8'
gem 'draper'
gem 'faraday'
gem 'apipie-rails', '~> 0.5'
gem 'maruku', require: false
gem 'active_attr'
gem 'aws-sdk-rails', '~> 3.6'
gem 'aws-sdk-s3', '~> 1.88', '>= 1.88.2'
gem 'hashie', '~> 3.4.0'
gem 'interactor-initializer', '~> 0.4.0'
gem 'jwt', '~> 2.2'
gem 'doorkeeper', '~> 5.3.3'
gem 'doorkeeper-grants_assertion', '~> 0.3.0'
gem 'oauth2', '~> 1.4.7'
gem 'zip_tricks', '4.6.0'
gem 'google-cloud-storage', '~> 1.25', require: 'google/cloud/storage'

gem 'sidekiq', '~> 5.2.0'
gem 'sidekiq-failures', '~> 1.0'
gem 'sidekiq-cron', '~> 1.0'
gem 'sidekiq-monitor-stats', '~> 0.0.2'
gem 'sidekiq-pool', '~> 1.9'
gem 'rufus-scheduler', '~> 3.5.0'

gem 'activejob'
gem 'chained_job', '~> 0.7.0'
gem 'sitemap_generator', '~> 5.0.0'
gem 'fog-rackspace'
gem 'net-sftp', '~> 2.1.2'
gem 'twitter-text', '~> 1.9.0'
gem 'koala', '~> 2.0.0'
gem 'searchlight', '~> 3.1.0'
gem 'auto_strip_attributes', '~> 2.0.0'
gem 'text', '~> 1.3.0'
gem 'uuidtools', '~> 2.2.0'
gem 'versionomy', '0.5.0'
gem 'fast_trie', '~> 0.5.0'
gem 'vinted-blurrily', require: 'blurrily/map'
gem 'httpclient', '~> 2.8.1'
gem 'money', '~> 6.5'
gem 'responders'
gem 'biz'
gem 'holidays'
gem 'vinted-crummy', require: 'crummy'
gem 'ancestry', '~> 4.0.0'
gem 'iban-tools', '~> 1.1.0'
gem 'nexmo', '~> 5.9'
gem 'phonelib'
gem 'sql_fingerprint', '~> 0.1'
gem 'http-accept', '~> 1.7'
gem 'semian', require: %w(semian semian/mysql2 semian/net_http)
gem 'damerau-levenshtein', '~> 1.3.3'

gem 'will_paginate'

gem 'elasticsearch', '~> 7.9.0'
gem 'elasticsearch-model'
gem 'elasticsearch-rails'
gem 'elasticsearch-api', '~> 7.9'

gem 'ruby-prof', require: false
gem 'ruby-prof-speedscope', require: false
gem 'stackprof', require: false
gem 'coverband'

gem 'impala', '~> 0.5.0'

gem 'ruby-kafka', '~> 1.4.0'

gem 'mimemagic', '~> 0.3.10'
gem 'msgpack', '~> 1.4.2'

gem 'lru_redux', '~> 1.1'
gem 'loc', '~> 0.1.1'

gem 'rack-proxy', '~> 0.6.5'

# private gems block
source private_gem_source do
  gem 'datadog_method_tracer'
  gem 'sidekiq-pro', '~> 4.0'
  gem 'vinted-admin_client', '~> 0.4.0'
  gem 'vinted-event_tracker', '~> 0.3.0', require: 'event_tracker'
  gem 'vinted-kafka', '~> 0.6.0'
  gem 'vinted-logger', '~> 0.8.0'
  gem 'vinted-metrics', '~> 3.2.0'
  gem 'vinted-online_schema_change', '~> 0.38.0'
  gem 'vinted-svc_client', '~> 0.20.0'
  gem 'vinted-svc_shipping_client', '~> 3.9.2'
  gem 'vinted-vitess_adapter', '~> 0.4.0'
end

# assets group is removed in rails 4.0
# but is still needed for compass (0.13.alpha, 1.0.0.alpha)
group :assets do
  gem 'browserify-rails'
  gem 'sprockets-rails', require: 'sprockets/railtie'
  gem 'sprockets', '>= 3.7'

  # generates nondigest assets
  gem 'non-stupid-digest-assets', '~> 1.0.4'
  gem 'sassc-rails'
  gem 'uglifier'
end

group :test, :development do
  gem 'rspec-rails', '>= 5.0.1'
  gem 'factory_bot_rails'
  gem 'launchy'
  gem 'listen'
  gem 'simplecov', require: false
  gem 'simplecov-lcov', require: false
  gem 'undercover', require: false
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'jasmine'
  gem 'jasmine-core', require: false
  gem 'jasmine_junitxml_formatter'
  gem 'packwerk', '~> 2.0.0'
  gem 'graphwerk'
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-remote'
  gem 'pronto'
  gem 'parser', '~> 2.7.2.0'
  gem 'pronto-rubocop', require: false
  gem 'pronto-flay', require: false
  gem 'pronto-brakeman', require: false
  # gem 'pronto-rails_schema', require: false
  gem 'pronto-rails_migrations', '>= 0.12.0', require: false
  gem 'pronto-eslint', require: false
  gem 'pronto-eslint_npm', require: false
  gem 'pronto-undercover', require: false
  gem 'pronto-packwerk', require: false, source: private_gem_source
  gem 'rubocop-rails', require: false
  gem 'rubocop-vinted', require: false, source: private_gem_source
  gem 'awesome_print'
  gem 'benchmark-ips'
  gem 'table_print'
  gem 'toxiproxy'
end

group :test do
  gem 'parallel_tests'
  gem 'mock_redis'
  gem 'webmock', require: false
  gem 'rspec-its'
  gem 'rspec-collection_matchers'
  gem 'rspec-activemodel-mocks'
  gem 'rspec-instrumentation-matcher'
  gem 'rails-controller-testing', require: false
  gem 'json_spec'
  gem 'ci_reporter_rspec'
  gem 'timecop'
  gem 'shoulda-matchers'
end

group :development do
  gem 'letter_opener'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'foreman'
  gem 'subcontractor'
  gem 'seedbank'
  gem 'bullet'
  gem 'traceroute'
  gem 'unicorn-rails'
  gem 'rb-readline'
  gem 'ruby-debug-ide'
  gem 'debase'
end
